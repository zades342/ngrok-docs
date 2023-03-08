
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2MkSBDdBSn0JWwbSYo0J7uNjKWc"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2MkSBGthwWrgeU10SXkegroZigX/ip_restriction
