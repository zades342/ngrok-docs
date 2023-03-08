
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2MkSBBgRbxqcp2f6NOLSLBlT3TO"]}' \
https://api.ngrok.com/edges/https/edghts_2MkSBAK0COXy9VmKAhMt3biS8MI/mutual_tls
