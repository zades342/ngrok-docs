<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-09T00:26:01Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2c6iK525oYCRkLXmB8Qh4qrLdPU",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c6iK525oYCRkLXmB8Qh4qrLdPU"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2c6iId5Fuxy7UwVJRJcXSUcAQM3",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2c6iId5Fuxy7UwVJRJcXSUcAQM3"
				},
				"enabled": true
			},
			"created_at": "2024-02-09T00:25:49Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2c6iIb8FnjH11RZESgZ5lbZFI2F",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c6iIb8FnjH11RZESgZ5lbZFI2F"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
