<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"enabled": true,
	"inbound": [
		{
			"actions": [
				{
					"config": {
						"metadata": {
							"edgeId": "edgtls_2j6lu2Tw5l4RHRCIOOKXJubxWcB",
							"message": "Invalid TLS Version"
						}
					},
					"type": "log"
				},
				{
					"type": "deny"
				}
			],
			"expressions": ["conn.tls.version.contains('1.3')"],
			"name": "AllowTLS1.3"
		}
	],
	"outbound": null
}
```
