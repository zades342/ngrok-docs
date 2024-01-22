<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"inbound":[{"expressions":["conn.TLS.CertCN != \"expected-cert-cn\"","conn.TLS.CipherSuite != \"expected-cipher-suite\"","conn.TLS.Version != \"expected-version\"","conn.TLS.SNI != \"expected-sni\""],"actions":[{"type":"log","config":{"Metadata":{"Message":"Invalid TLS Info"}}},{"type":"deny"}],"name":"Conns Has Incorrect TLS Info"}],"outbound":[{"expressions":["conn.ClientIP == '192.0.2.0'","conn.ClientIP == '198.51.100.0'"],"actions":[{"type":"log","config":{"Metadata":{"Message":"Outbound Connection to Speicified IP"}}}],"name":"Log Outbound Connection To Specific IPs"}]}' \
https://api.ngrok.com/edges/tls/edgtls_2bIPjDe1wvBGw4BpUmazFQtYSHx/policies
```
