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
					"started_at": "2024-05-29T18:50:13Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5fyvkk7ul3tqnvlpz.local-ngrok-cname.com",
			"created_at": "2024-05-29T18:50:13Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2h9aBqA8jEks7LiVR8eSaJ5m3L0",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2h9aBqA8jEks7LiVR8eSaJ5m3L0"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2h9aBbwOfIjDM8KP5EMg8CCmceM",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2h9aBbwOfIjDM8KP5EMg8CCmceM"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5fyvkk7ul3tqnvlpz.local-ngrok-cname.com",
			"created_at": "2024-05-29T18:50:12Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2h9aBkdsiRNMqtatMyUENHzZElN",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2h9aBkdsiRNMqtatMyUENHzZElN"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
