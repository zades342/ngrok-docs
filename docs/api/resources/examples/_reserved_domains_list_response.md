<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2c8f2uVWimkkRrRH9IQma1vs7aD",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2c8f2uVWimkkRrRH9IQma1vs7aD"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.5ejdzz1berosqyxxh.local-ngrok-cname.com",
			"created_at": "2024-02-09T16:58:43Z",
			"domain": "myapp.mydomain.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2c8f33mKZAi9ONysnLCfqN5I9Pq",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2c8f33mKZAi9ONysnLCfqN5I9Pq"
		},
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
					"started_at": "2024-02-09T16:58:43Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.5ejdzz1berosqyxxh.local-ngrok-cname.com",
			"created_at": "2024-02-09T16:58:43Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2c8f31AEYmpbbttwwL8tV90dMRx",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2c8f31AEYmpbbttwwL8tV90dMRx"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
