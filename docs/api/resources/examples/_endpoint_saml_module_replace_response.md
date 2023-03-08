
#### Example Response
```json
{
  "enabled": true,
  "options_passthrough": false,
  "cookie_prefix": "",
  "inactivity_timeout": 0,
  "maximum_duration": 0,
  "idp_metadata_url": "",
  "idp_metadata": "\n\u003cEntityDescriptor xmlns=\"urn:oasis:names:tc:SAML:2.0:metadata\" validUntil=\"2020-09-14T12:53:23.691Z\" cacheDuration=\"PT1M\" entityID=\"http://127.0.0.1:12345/metadata\"\u003e\u003cIDPSSODescriptor xmlns=\"urn:oasis:names:tc:SAML:2.0:metadata\" protocolSupportEnumeration=\"urn:oasis:names:tc:SAML:2.0:protocol\"\u003e\u003cNameIDFormat\u003eurn:oasis:names:tc:SAML:2.0:nameid-format:transient\u003c/NameIDFormat\u003e\u003cSingleSignOnService Binding=\"urn:oasis:names:tc:SAML:2.0:bindings:HTTP-Redirect\" Location=\"http://127.0.0.1:12345/sso\"\u003e\u003c/SingleSignOnService\u003e\u003cSingleSignOnService Binding=\"urn:oasis:names:tc:SAML:2.0:bindings:HTTP-POST\" Location=\"http://127.0.0.1:12345/sso\"\u003e\u003c/SingleSignOnService\u003e\u003c/IDPSSODescriptor\u003e\u003c/EntityDescriptor\u003e\n",
  "force_authn": false,
  "allow_idp_initiated": true,
  "authorized_groups": [],
  "entity_id": "https://idp.local-ngrok.com/saml/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY",
  "assertion_consumer_service_url": "https://idp.local-ngrok.com/saml/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY/acs",
  "single_logout_url": "https://idp.local-ngrok.com/saml/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY/slo",
  "request_signing_certificate_pem": "-----BEGIN CERTIFICATE-----\nMIID6zCCAtOgAwIBAgIQMxlqfX4dHqC4SPH43QxTNTANBgkqhkiG9w0BAQsFADCB\nlDFIMEYGA1UECgw/aHR0cHM6Ly9pZHAubG9jYWwtbmdyb2suY29tL3NhbWwvZWNf\nMk1rU0FHaWRiUGVOYUdBNVFuZGk1eVBtN09ZMUgwRgYDVQQDDD9odHRwczovL2lk\ncC5sb2NhbC1uZ3Jvay5jb20vc2FtbC9lY18yTWtTQUdpZGJQZU5hR0E1UW5kaTV5\nUG03T1kwIBcNMjMwMzA4MjExMjIyWhgPMjA1ODAyMjcyMTEyMjJaMIGUMUgwRgYD\nVQQKDD9odHRwczovL2lkcC5sb2NhbC1uZ3Jvay5jb20vc2FtbC9lY18yTWtTQUdp\nZGJQZU5hR0E1UW5kaTV5UG03T1kxSDBGBgNVBAMMP2h0dHBzOi8vaWRwLmxvY2Fs\nLW5ncm9rLmNvbS9zYW1sL2VjXzJNa1NBR2lkYlBlTmFHQTVRbmRpNXlQbTdPWTCC\nASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBALQBtAOyYNQz/gs40j0ZFo0D\nVTPU/mU8sKwhAezUMi/gL3KIhyMzEIp9axlxzz7Ni9wWOgOoYzptenBQNtDBQV6j\ntx9gYR6gkkAaXYnt3LUc0yzgUjNa7p/H5IgEiGPeX+zGV2V314ykdVSi3KNNpqin\niaZToCMD8S8fJnMAdbhhGHCk5OFTd1+2fghUhtYN8UPc3hLvwmRxCAQ2TJlvPYSB\n6zCoupThxYLQTM0o5ztx+j2eYt6ZNIRlSVWv9QW6qt3VgmuX6TZfyQGUHgvHVbL8\n4hW7r4s8C7A6thrJ7d/OYmlI/4qDEv633ezXUROp+lzpf3i+3wQlRWaoPI6lW58C\nAwEAAaM1MDMwDgYDVR0PAQH/BAQDAgeAMBMGA1UdJQQMMAoGCCsGAQUFBwMBMAwG\nA1UdEwEB/wQCMAAwDQYJKoZIhvcNAQELBQADggEBAGNWEjhMbM0KvpT7H2usLHea\nnNHiLoYCVhBRdULX2SQMg86apZ+xgrMp+l7aoDKVwGYZuXMYCjJwP0JGjTINZ8ZM\n9/VyZLFahEIIiTzIHOjxDhB/xjDAspXGQDlTZ3tPdm+wY/FAzRT2210md2T7tJj1\nDjhUIeNFW6C+ujBtZyW5+opbduh3FABZ49KfbFC35XKGN68tn7SZB2aOxwJUkIeC\nNI8smvgSA/ZiFqY+TVzJCv2CRaubj8JxFjye75Bh+J2EVWIEScvo65ydPYszHjGu\nPmTNOZf9gph+SqW0GNF3DtfY5wTUA4q4DNBX75XyASMHhf5mIvjLXnSFa/6wBwI=\n-----END CERTIFICATE-----\n",
  "metadata_url": "https://idp.local-ngrok.com/saml/ec_2MkSAGidbPeNaGA5Qndi5yPm7OY",
  "nameid_format": "urn:oasis:names:tc:SAML:2.0:nameid-format:persistent"
}