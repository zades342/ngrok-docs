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
					"started_at": "2024-07-11T16:33:18Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.39yxrdwsjfwgsxkaq.local-ngrok-cname.com",
			"created_at": "2024-07-11T16:33:18Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2j6lqXMGMsRRPRwJu0WwiJ4PbpI",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2j6lqXMGMsRRPRwJu0WwiJ4PbpI"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2j6lqXZVLuAwXvlI1mm5I8KwEph",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2j6lqXZVLuAwXvlI1mm5I8KwEph"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.39yxrdwsjfwgsxkaq.local-ngrok-cname.com",
			"created_at": "2024-07-11T16:33:18Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2j6lqcnarf0E0dv4j8q0Cz4zuzI",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2j6lqcnarf0E0dv4j8q0Cz4zuzI"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
