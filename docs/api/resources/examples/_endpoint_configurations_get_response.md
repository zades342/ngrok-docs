
#### Example Response
```json
{
  "id": "ec_2MkS9OW1EZsw6THWCTRWELYZANl",
  "type": "https",
  "description": "app servers",
  "created_at": "2023-03-08T21:12:14Z",
  "uri": "https://api.ngrok.com/endpoint_configurations/ec_2MkS9OW1EZsw6THWCTRWELYZANl",
  "basic_auth": null,
  "circuit_breaker": null,
  "compression": null,
  "request_headers": {
    "enabled": true,
    "add": {
      "x-frontend": "ngrok"
    },
    "remove": [
      "cache-control"
    ]
  },
  "response_headers": null,
  "ip_policy": {
    "enabled": true,
    "ip_policies": [
      {
        "id": "ipp_2MkS9JCPNfROHT07MvJsdhQMJjB",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2MkS9JCPNfROHT07MvJsdhQMJjB"
      }
    ]
  },
  "mutual_tls": null,
  "tls_termination": null,
  "webhook_validation": null,
  "oauth": null,
  "saml": null,
  "oidc": null,
  "backend": null
}