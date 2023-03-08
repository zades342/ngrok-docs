
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
  "entity_id": "https://idp.local-ngrok.com/saml/edghtsrt_2MkSAwoUFpZwOBN5uxGKNxinyUF",
  "assertion_consumer_service_url": "https://idp.local-ngrok.com/saml/edghtsrt_2MkSAwoUFpZwOBN5uxGKNxinyUF/acs",
  "single_logout_url": "https://idp.local-ngrok.com/saml/edghtsrt_2MkSAwoUFpZwOBN5uxGKNxinyUF/slo",
  "request_signing_certificate_pem": "-----BEGIN CERTIFICATE-----\nMIIEAzCCAuugAwIBAgIQXtHMsDFns3pmnz9Xpy0IqTANBgkqhkiG9w0BAQsFADCB\noDFOMEwGA1UECgxFaHR0cHM6Ly9pZHAubG9jYWwtbmdyb2suY29tL3NhbWwvZWRn\naHRzcnRfMk1rU0F3b1VGcFp3T0JONXV4R0tOeGlueVVGMU4wTAYDVQQDDEVodHRw\nczovL2lkcC5sb2NhbC1uZ3Jvay5jb20vc2FtbC9lZGdodHNydF8yTWtTQXdvVUZw\nWndPQk41dXhHS054aW55VUYwIBcNMjMwMzA4MjExMjI3WhgPMjA1ODAyMjcyMTEy\nMjdaMIGgMU4wTAYDVQQKDEVodHRwczovL2lkcC5sb2NhbC1uZ3Jvay5jb20vc2Ft\nbC9lZGdodHNydF8yTWtTQXdvVUZwWndPQk41dXhHS054aW55VUYxTjBMBgNVBAMM\nRWh0dHBzOi8vaWRwLmxvY2FsLW5ncm9rLmNvbS9zYW1sL2VkZ2h0c3J0XzJNa1NB\nd29VRnBad09CTjV1eEdLTnhpbnlVRjCCASIwDQYJKoZIhvcNAQEBBQADggEPADCC\nAQoCggEBAOWSVPl2ksbamL2S8JkmUX6nq6P0sszdeYqNjHkS0NPfOlA5Q6+6Nyec\nrQGPbi54RpS6QwlpZwuuNB7lwCHLlKDiDyPWQZ3BFbHC0pdnvc5mh6z29Cmi/pge\nY3P9dSPaWahZacHX61ww7+KxaBUY41RAR3KJ2WcXFH2S6bJB9TTC0z51Ktv4PjWz\nsT36dCoD1+h9h/AOqMnvUpYbBDGrlihQdyn9XMxZ/g/Y6U5FWDNc616xZI0u4DBO\nPjjsDbgJiLGhGxLyOdti4IlzGJEFplPEW0shKt6jmCKsnzUQ5PQQEhExuBDRB4WF\nbiZVtImqSvw+sLZXIWXZm8gtnczeHrsCAwEAAaM1MDMwDgYDVR0PAQH/BAQDAgeA\nMBMGA1UdJQQMMAoGCCsGAQUFBwMBMAwGA1UdEwEB/wQCMAAwDQYJKoZIhvcNAQEL\nBQADggEBAH5V0mnED6ncdkmDmg8r5e6cUfm6/NPlhYhzCaKkUygQzQtu0xxJFi/J\n/Kboojuh0L7oHD71NxaXqaAj1j2A1VcW1zWq9PX5yVeCrITaY5vvMMWd/+ZUgih2\n4PfIlMJ2q1RAQkoQKDKuwL40U7gl5E7WU4AUGE7hhc+18WtjVs0SecYjuVlVTbjC\n5k7DJ8FbGvafrugMVvEh9VQr+uzDAS7PTFI89nUGEIcc5S4QpsxjWMyB17GR41pY\n/Shi9e/SLGc8cfwxNJkE6KIZgaNE7p8QpgOsIo9MLYqfRshCcl6fwe59clGYQHM7\nZ9Udr0TwCJrSovbqIwi0ahzPaqqueAU=\n-----END CERTIFICATE-----\n",
  "metadata_url": "https://idp.local-ngrok.com/saml/edghtsrt_2MkSAwoUFpZwOBN5uxGKNxinyUF",
  "nameid_format": "urn:oasis:names:tc:SAML:2.0:nameid-format:persistent"
}