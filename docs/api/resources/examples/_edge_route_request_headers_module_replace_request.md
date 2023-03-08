
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"x-frontend":"ngrok"},"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2MkSAqJpj66IxH1pt6qElE3T4HT/routes/edghtsrt_2MkSApc5SgsEQdqIQ4XjTOdBssX/request_headers
