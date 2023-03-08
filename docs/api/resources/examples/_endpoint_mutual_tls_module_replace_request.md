
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2MkSAH1Xw57d3szRXmxoCqAuEHS"]}' \
https://api.ngrok.com/endpoint_configurations/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY/mutual_tls
