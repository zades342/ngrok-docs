
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "id": "esb_2MkSAKEcU17bPa4VNHFFf95SkqM",
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2MkSAKEcU17bPa4VNHFFf95SkqM",
      "created_at": "2023-03-08T21:12:22Z",
      "metadata": "{\"environment\": \"staging\"}",
      "description": "ip policy creations",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2MkSAKEcU17bPa4VNHFFf95SkqM/sources/ip_policy_created.v0"
        }
      ],
      "destinations": [
        {
          "id": "ed_2MkSAM6oPybAiy0sQbODsmfkSVF",
          "uri": "https://api.ngrok.com/event_destinations/ed_2MkSAM6oPybAiy0sQbODsmfkSVF"
        }
      ]
    }
  ],
  "uri": "https://api.ngrok.com/event_subscriptions",
  "next_page_uri": null
}