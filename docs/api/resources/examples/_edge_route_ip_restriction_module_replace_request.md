
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2MkSAila5vrTQ6sSid4n7W6HcyJ","ipp_2MkSAhhffuPtczudt50zlEzrZDe"]}' \
https://api.ngrok.com/edges/https/edghts_2MkSAjvbcsB71coBKKP9Mx5dlDn/routes/edghtsrt_2MkSAi7WPR4Yg62qpL5KbbvgIWQ/ip_restriction
