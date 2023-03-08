
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2MkSBP0WGMCe2q66xtule9OICCJ"]}' \
https://api.ngrok.com/edges/tls/edgtls_2MkSBMYITUtQ8cbq8YWNSLzjEFu/mutual_tls
