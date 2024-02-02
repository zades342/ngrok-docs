<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-02-02T16:02:47Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2bomNneFR7vBWfH2AxyX6EtLMax",
					"uri": "https://api.ngrok.com/event_destinations/ed_2bomNneFR7vBWfH2AxyX6EtLMax"
				}
			],
			"id": "esb_2bomNjLhPX03X3HSItbyvN2xlEb",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2bomNjLhPX03X3HSItbyvN2xlEb/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2bomNjLhPX03X3HSItbyvN2xlEb"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
