<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-14T10:06:57Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2x59lOMy6znG8p06jasxdVk6oZv",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2x59lOMy6znG8p06jasxdVk6oZv"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2x59k5yFnKKb0wTYMyiuS5iDiJr",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2x59k5yFnKKb0wTYMyiuS5iDiJr"
        },
        "enabled": true
      },
      "created_at": "2025-05-14T10:06:47Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2x59k9B3L9o42CHyBQDaOo6y1QG",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2x59k9B3L9o42CHyBQDaOo6y1QG"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
