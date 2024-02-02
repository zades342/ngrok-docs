<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-02T16:02:54Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2bomOfbEB6uoY2JXh67hdeawWaj",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bomOfbEB6uoY2JXh67hdeawWaj"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2bomMyHZ50jkyXB7QiRTd9ysJcc",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2bomMyHZ50jkyXB7QiRTd9ysJcc"
				},
				"enabled": true
			},
			"created_at": "2024-02-02T16:02:41Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2bomN1NbIg1cZs1VugmImD4uFNX",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2bomN1NbIg1cZs1VugmImD4uFNX"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
