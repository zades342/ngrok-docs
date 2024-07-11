<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-07-11T16:33:45Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2j6ltwo03TVc7U31r51esZc1UvW",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2j6ltwo03TVc7U31r51esZc1UvW"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2j6lscW3kciXZLMeoS5ZaDjdCHc",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2j6lscW3kciXZLMeoS5ZaDjdCHc"
				},
				"enabled": true
			},
			"created_at": "2024-07-11T16:33:34Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2j6lsdICzAk9LhZhoOeCvm0k3Bl",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2j6lsdICzAk9LhZhoOeCvm0k3Bl"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
