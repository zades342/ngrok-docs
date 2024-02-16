<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-02-16T22:24:01Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2cT4TQDKTqBYk5ON3Sf4lbJTTTC",
					"uri": "https://api.ngrok.com/event_destinations/ed_2cT4TQDKTqBYk5ON3Sf4lbJTTTC"
				}
			],
			"id": "esb_2cT4TNxPcVtu7MgSxTOnHPlTcJB",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2cT4TNxPcVtu7MgSxTOnHPlTcJB/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2cT4TNxPcVtu7MgSxTOnHPlTcJB"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
