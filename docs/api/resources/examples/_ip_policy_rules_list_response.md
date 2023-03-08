
#### Example Response
```json
{
  "ip_policy_rules": [
    {
      "id": "ipr_2MkSAFgORK0V58tLCEFufjYcaE5",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2MkSAFgORK0V58tLCEFufjYcaE5",
      "created_at": "2023-03-08T21:12:21Z",
      "description": "sf office",
      "cidr": "132.2.19.0/24",
      "ip_policy": {
        "id": "ipp_2MkSAH8duI14geiNhgiaKGYAwDQ",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2MkSAH8duI14geiNhgiaKGYAwDQ"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2MkSACu84LCOGw8HKWH5e1rfun8",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2MkSACu84LCOGw8HKWH5e1rfun8",
      "created_at": "2023-03-08T21:12:21Z",
      "description": "nyc office",
      "cidr": "212.3.14.0/24",
      "ip_policy": {
        "id": "ipp_2MkSAH8duI14geiNhgiaKGYAwDQ",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2MkSAH8duI14geiNhgiaKGYAwDQ"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2MkSAByxmkIGZfPdlTbGN4r0Ter",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2MkSAByxmkIGZfPdlTbGN4r0Ter",
      "created_at": "2023-03-08T21:12:21Z",
      "description": "alan laptop",
      "cidr": "2.2.2.2/32",
      "ip_policy": {
        "id": "ipp_2MkSAH8duI14geiNhgiaKGYAwDQ",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2MkSAH8duI14geiNhgiaKGYAwDQ"
      },
      "action": "allow"
    }
  ],
  "uri": "https://api.ngrok.com/ip_policy_rules",
  "next_page_uri": null
}