<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-09T16:59:11Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2c8f6bKIBYCQG2hUoHvyKmc0mcL",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c8f6bKIBYCQG2hUoHvyKmc0mcL"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2c8f55PnpNd5oXFMjS2SLmWhAHl",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2c8f55PnpNd5oXFMjS2SLmWhAHl"
				},
				"enabled": true
			},
			"created_at": "2024-02-09T16:58:59Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2c8f53DmQPTIxJ9QLP7ZKtcFYKE",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c8f53DmQPTIxJ9QLP7ZKtcFYKE"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
