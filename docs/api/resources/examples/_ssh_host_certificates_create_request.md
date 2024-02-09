<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"personal server","principals":["inconshreveable.com","10.2.42.9"],"public_key":"ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBI3oSgxrOEJ+tIJ/n6VYtxQIFvynqlOHpfOAJ4x4OfmMYDkbf8dr6RAuUSf+ZC2HMCujta7EjZ9t+6v08Ue+Cgk= inconshreveable.com","ssh_certificate_authority_id":"sshca_2c8f5pUZEAQXwATKojI5HXp2AYB","valid_until":"2024-05-09T16:59:05Z"}' \
https://api.ngrok.com/ssh_host_certificates
```
