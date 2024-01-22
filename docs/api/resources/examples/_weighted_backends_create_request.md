<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme weighted","metadata":"{\"environment\": \"staging\"}","backends":{"bkdhr_2bIPiItxoCqB2jhEh0ZS8JMkZZT":1,"bkdhr_2bIPiKN7lX1RY6OSk0kNWNdV4a7":0}}' \
https://api.ngrok.com/backends/weighted
```
