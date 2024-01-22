<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"id": "ec_2bIPfSJp0LXCFyMgF0xCMBKFWtt",
	"type": "https",
	"description": "app servers",
	"created_at": "2024-01-22T05:02:02Z",
	"uri": "https://api.ngrok.com/endpoint_configurations/ec_2bIPfSJp0LXCFyMgF0xCMBKFWtt",
	"basic_auth": null,
	"circuit_breaker": null,
	"compression": null,
	"request_headers": {
		"enabled": true,
		"add": {
			"x-frontend": "ngrok"
		},
		"remove": ["cache-control"]
	},
	"response_headers": null,
	"ip_policy": {
		"enabled": true,
		"ip_policies": [
			{
				"id": "ipp_2bIPfT8axaL0VpHEuT4mwEkYfC7",
				"uri": "https://api.ngrok.com/ip_policies/ipp_2bIPfT8axaL0VpHEuT4mwEkYfC7"
			}
		]
	},
	"mutual_tls": null,
	"tls_termination": null,
	"webhook_validation": null,
	"oauth": null,
	"saml": null,
	"oidc": null,
	"backend": null
}
```
