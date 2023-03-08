
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true}' \
https://api.ngrok.com/edges/https/edghts_2MkSB6jRgKhQvqxLB6RbFo8VRDY/routes/edghtsrt_2MkSB91a0MNmlCJSOLCFhX9EShs/websocket_tcp_converter
