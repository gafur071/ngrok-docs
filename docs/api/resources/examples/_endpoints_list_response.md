<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-14T10:06:52Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2x59k7dBXEPnL5gHP9gB6KoPRDz",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2x59k7dBXEPnL5gHP9gB6KoPRDz"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2x59kkQvh10ctLBLceowuw5UEhf",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-14T10:06:52Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2x59kkQvh10ctLBLceowuw5UEhf",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-14T10:06:51Z",
      "hostport": "1822151f6868.ngrok.paid:443",
      "id": "ep_2x59kftWIIGelTsUIllr2aot6As",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2x59i4rx1p0lS5AUDOJNMhmHpuz",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://1822151f6868.ngrok.paid",
      "tunnel": {
        "id": "tn_2x59kftWIIGelTsUIllr2aot6As",
        "uri": "https://api.ngrok.com/tunnels/tn_2x59kftWIIGelTsUIllr2aot6As"
      },
      "tunnel_session": {
        "id": "ts_2x59kb8gzqUCs65xIso14bfalQ7",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2x59kb8gzqUCs65xIso14bfalQ7"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-14T10:06:51Z",
      "upstream_url": "http://localhost:80",
      "url": "https://1822151f6868.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-14T10:06:47Z",
      "domain": {
        "id": "rd_2x59k7dBXEPnL5gHP9gB6KoPRDz",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2x59k7dBXEPnL5gHP9gB6KoPRDz"
      },
      "edge": {
        "id": "edgtls_2x59k9B3L9o42CHyBQDaOo6y1QG",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2x59k9B3L9o42CHyBQDaOo6y1QG"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2x59kAxjIKHQnCP7QB9WdATWFdC",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-14T10:06:47Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
