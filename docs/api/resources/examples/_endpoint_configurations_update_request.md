
#### Example Request
```bash
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy":{"ip_policy_ids":["ipp_2MkS9JCPNfROHT07MvJsdhQMJjB"]}}' \
https://api.ngrok.com/endpoint_configurations/ec_2MkS9OW1EZsw6THWCTRWELYZANl
