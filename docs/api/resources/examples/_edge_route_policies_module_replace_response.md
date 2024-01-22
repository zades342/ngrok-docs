<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"expressions": [
				"req.Method == \"POST\" \u0026\u0026 req.ContentLength \u003e 10000",
				"conn.Geo.CountryCode in ['BR', 'CN', 'CU', 'IR', 'NG', 'RO', 'RU', 'SD', 'SY', 'UA']"
			],
			"actions": [
				{
					"type": "custom-response",
					"config": {
						"content": "access denied",
						"content_type": "text/plain",
						"status_code": 401
					}
				}
			],
			"name": "Block POST Requests With Large Content Length From Specific Countries."
		},
		{
			"expressions": [
				"\"SuspiciousAgent\" in req.Headers[\"User-Agent\"]",
				"\"BadActor\" in req.Headers[\"User-Agent\"]",
				"\"RudeDudes\" in req.Headers[\"User-Agent\"]",
				"\"Scalawags\" in req.Headers[\"User-Agent\"]"
			],
			"actions": [
				{
					"type": "deny",
					"config": {
						"status_code": 400
					}
				}
			],
			"name": "Block User Agents."
		}
	],
	"outbound": [
		{
			"expressions": ["res.ContentLength \u003c 500000"],
			"actions": [
				{
					"type": "log",
					"config": {
						"Metadata": {
							"Message": "response exceeded threshold."
						}
					}
				}
			],
			"name": "Log When Response Size \u003c 500000"
		}
	]
}
```
