<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-16T22:24:06Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2cT4U2rmLTjFN7B6nb9ogwm7gnz",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2cT4U2rmLTjFN7B6nb9ogwm7gnz"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2cT4SjaRHyKqcaTx2HTAt7dILqu",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2cT4SjaRHyKqcaTx2HTAt7dILqu"
				},
				"enabled": true
			},
			"created_at": "2024-02-16T22:23:55Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2cT4ScKllS7wIVk3OheQYm9gLkn",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2cT4ScKllS7wIVk3OheQYm9gLkn"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
