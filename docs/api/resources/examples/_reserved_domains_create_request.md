
#### Example Request
```bash
curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"domain":"myapp.mydomain.com","region":"us","certificate_id":"cert_2MkS9LND8wxIN7TKxZGxC0xvWp2"}' \
https://api.ngrok.com/reserved_domains
