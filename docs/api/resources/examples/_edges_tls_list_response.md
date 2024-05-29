<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-05-29T18:50:39Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2h9aF6yNKzAhbXiBOvMGD6SWSzP",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2h9aF6yNKzAhbXiBOvMGD6SWSzP"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2h9aDcEiStVOfwTxNXd97z20dWd",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2h9aDcEiStVOfwTxNXd97z20dWd"
				},
				"enabled": true
			},
			"created_at": "2024-05-29T18:50:28Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2h9aDfS4iTVLuv1cxnJiRdU8j30",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2h9aDfS4iTVLuv1cxnJiRdU8j30"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
