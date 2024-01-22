<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"provider":{"google":{"client_id":"client-id","client_secret":"client-secret","scopes":["profile","email","https://www.googleapis.com/auth/userinfo.email"],"email_addresses":["alan@example.com"]}}}' \
https://api.ngrok.com/edges/https/edghts_2bIPilQ08GspsgRMlYlHRyulftW/routes/edghtsrt_2bIPigBueiicFHEf2xxd4CSuo6C/oauth
```
