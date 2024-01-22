<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"expressions": [
				"conn.Geo.Latitude \u003e= \"45.0\" \u0026\u0026 conn.Geo.Longitude \u003c= \"-93.0\""
			],
			"actions": [
				{
					"type": "deny",
					"config": null
				}
			],
			"name": "Block Inbound Traffic From Specific Geographical Area."
		}
	],
	"outbound": [
		{
			"expressions": [
				"conn.Geo.CountryCode in [\"US\", \"CA\", \"MX\", \"GT\", \"BZ\", \"SV\"] \u0026\u0026 conn.ClientIP == \"192.0.2.0\""
			],
			"actions": [
				{
					"type": "log",
					"config": {
						"Metadata": {
							"Message": "Outbound Traffic to North America with IP 192.0.2.0"
						}
					}
				}
			],
			"name": "Log Outbound Traffic From Specific Country Codes"
		}
	]
}
```
