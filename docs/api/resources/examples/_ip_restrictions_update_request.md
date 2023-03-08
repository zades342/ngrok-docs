
#### Example Request
```bash
curl \
-XPATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ip_policy_ids":["ipp_2MkSAPeuKgzeBOJXW3Yzo33eMkw","ipp_2MkSAOXGxgU6bhie1dwGnqG3Cgc"]}' \
https://api.ngrok.com/ip_restrictions/ipx_2MkSAKrjWDmQiHrzYBPmGDQRoEq
