<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-02-09T00:25:34Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3m4qe4epqqzkuejb5.local-ngrok-cname.com",
			"created_at": "2024-02-09T00:25:33Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2c6iGctgQ3A7DuveDM2GHSV4WH2",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2c6iGctgQ3A7DuveDM2GHSV4WH2"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2c6iGXOjZZDo0cJSV0rNhx3UeJP",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2c6iGXOjZZDo0cJSV0rNhx3UeJP"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3m4qe4epqqzkuejb5.local-ngrok-cname.com",
			"created_at": "2024-02-09T00:25:33Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2c6iGbV1MJw6FqFpNZdvvAxPJxX",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2c6iGbV1MJw6FqFpNZdvvAxPJxX"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
