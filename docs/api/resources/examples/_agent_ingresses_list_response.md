
#### Example Response
```json
{
  "ingresses": [
    {
      "id": "agin_2MkSAV3LvuuQayy7XwcmOeb6uYM",
      "uri": "https://api.ngrok.com/agent_ingresses/agin_2MkSAV3LvuuQayy7XwcmOeb6uYM",
      "description": "acme devices",
      "domain": "connect.acme.com",
      "ns_targets": [
        "1.kube-dns.kube-system.svc.cluster.local.",
        "2.kube-dns.kube-system.svc.cluster.local.",
        "3.kube-dns.kube-system.svc.cluster.local.",
        "4.kube-dns.kube-system.svc.cluster.local."
      ],
      "region_domains": [
        "tunnel.us.connect.acme.com"
      ],
      "created_at": "2023-03-08T21:12:23Z"
    }
  ],
  "uri": "https://api.ngrok.com/agent_ingresses",
  "next_page_uri": null
}