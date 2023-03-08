
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2MkSBFBcW0u32zBebgERJcPPaeI","ipp_2MkSBIOw6g3Hes9c8zejP7V5ID8"]}' \
https://api.ngrok.com/edges/tls/edgtls_2MkSBEojJsqGTBYU442u6Y8QUw0/ip_restriction
