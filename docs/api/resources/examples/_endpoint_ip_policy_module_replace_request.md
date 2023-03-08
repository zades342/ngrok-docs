
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy_ids":["ipp_2MkSAE545cxPmMJHYHTV15Qzp7n"]}' \
https://api.ngrok.com/endpoint_configurations/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY/ip_policy
