<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"tls_edges": [
		{
			"id": "edgtls_2bIPiyL7YtApbPHMTRQ4FehXljI",
			"description": "acme tls edge",
			"metadata": "{\"environment\": \"staging\"}",
			"created_at": "2024-01-22T05:02:30Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bIPiyL7YtApbPHMTRQ4FehXljI",
			"hostports": ["example.com:443"],
			"backend": null,
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policies": null
		},
		{
			"id": "edgtls_2bIPhWeq1BxF5W0lknkeyAGRFPj",
			"description": "acme tls edge",
			"created_at": "2024-01-22T05:02:18Z",
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bIPhWeq1BxF5W0lknkeyAGRFPj",
			"hostports": ["endpoint-example.com:443"],
			"backend": {
				"enabled": true,
				"backend": {
					"id": "bkdhr_2bIPhRgBiahVSZixzXQtq4h7pfJ",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2bIPhRgBiahVSZixzXQtq4h7pfJ"
				}
			},
			"ip_restriction": null,
			"mutual_tls": null,
			"tls_termination": null,
			"policies": null
		}
	],
	"uri": "https://api.ngrok.com/edges/tls",
	"next_page_uri": null
}
```
