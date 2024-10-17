<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2024-10-11T22:09:09Z",
	"description": "Sample Cloud Endpoint",
	"domain": {
		"id": "rd_2nJI2Vc4v6vcdB4eIUU3yWtGfYS",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2nJI2Vc4v6vcdB4eIUU3yWtGfYS"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2nJI38CweJI8NuL7rExaR62L6f2",
	"metadata": "{\"environment\": \"staging\"}",
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2024-10-11T22:09:09Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2nJI38CweJI8NuL7rExaR62L6f2",
	"url": "https://endpoint-example2.com"
}
```