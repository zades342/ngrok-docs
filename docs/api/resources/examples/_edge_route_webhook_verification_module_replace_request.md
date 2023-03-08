
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"provider":"TWILIO","secret":"secret_token"}' \
https://api.ngrok.com/edges/https/edghts_2MkSB1tbZ1bDliE8eStClIJqqXy/routes/edghtsrt_2MkSAweqCGMpgmZX1ahsjodPHvw/webhook_verification
