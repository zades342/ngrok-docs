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
					"started_at": "2024-02-02T16:02:26Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.sowjxkwmeq8aebf9.local-ngrok-cname.com",
			"created_at": "2024-02-02T16:02:25Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2bomL9fkuy0cLHI1BHEaoN36azx",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2bomL9fkuy0cLHI1BHEaoN36azx"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2bomKyp0oxhyTanKyfOx2NiDiGw",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2bomKyp0oxhyTanKyfOx2NiDiGw"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.sowjxkwmeq8aebf9.local-ngrok-cname.com",
			"created_at": "2024-02-02T16:02:25Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2bomKwQND8fkST6eycbyfTKVR30",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2bomKwQND8fkST6eycbyfTKVR30"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
