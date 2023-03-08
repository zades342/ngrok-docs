
#### Example Request
```bash
curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ssh_certificate_authority_id":"sshca_2MkSAURAcvLC4uNVeD0ho0v1s5v","public_key":"ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBK58lFzmWlDimDtBz78wVT4oauA8PjY0CiXTCEIsBNC6UwOJvZ0jdSaYNhDaa7dRV84DfBb/gKzqlXC7cVMZjl0= alan@work-laptop","principals":["ec2-user","root"],"valid_until":"2023-06-06T21:12:23Z","description":"temporary access to staging machine"}' \
https://api.ngrok.com/ssh_user_certificates
