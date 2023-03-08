
#### Example Request
```bash
curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"type":"ip_policy_updated.v0"}' \
https://api.ngrok.com/event_subscriptions/esb_2MkSAKG3ui79Bvo6a4WjWhhfYB9/sources
