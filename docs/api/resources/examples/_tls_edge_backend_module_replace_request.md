
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"backend_id":"bkdtg_2MkSBHZ78bnrTZ9Cqa8kEQvnvkH"}' \
https://api.ngrok.com/edges/tls/edgtls_2MkSBFeQkkOmqlCDwcdHv7difPa/backend
