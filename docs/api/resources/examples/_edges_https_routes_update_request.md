
#### Example Request
```bash
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"environment\": \"production\"}"}' \
https://api.ngrok.com/edges/https/edghts_2MkSAdflsh04DjhO448k68WLDfo/routes/edghtsrt_2MkSAdMkn3R6bY48lAmBigXgqAM
