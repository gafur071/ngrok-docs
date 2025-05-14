<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tunnels": [
    {
      "endpoint": {
        "id": "ep_2x59jCOr6jYA4fzqVsfnBb4Ib8z",
        "uri": "https://api.ngrok.com/endpoints/ep_2x59jCOr6jYA4fzqVsfnBb4Ib8z"
      },
      "forwards_to": "http://localhost:80",
      "id": "tn_2x59jCOr6jYA4fzqVsfnBb4Ib8z",
      "proto": "https",
      "public_url": "https://a59c4b286a56.ngrok.paid",
      "region": "us",
      "started_at": "2025-05-14T10:06:39Z",
      "tunnel_session": {
        "id": "ts_2x59j5rScybTheZN95cIW1CKmj3",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2x59j5rScybTheZN95cIW1CKmj3"
      }
    },
    {
      "forwards_to": "http://localhost:80",
      "id": "tn_2x59ibeuLg4vZyA05ZrLddYFNjN",
      "labels": {
        "baz": "qux",
        "foo": "bar"
      },
      "region": "us",
      "started_at": "2025-05-14T10:06:35Z",
      "tunnel_session": {
        "id": "ts_2x59ibJNw6xTmVHNhqXQ07Sa8cs",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2x59ibJNw6xTmVHNhqXQ07Sa8cs"
      }
    }
  ],
  "uri": "https://api.ngrok.com/tunnels"
}
```
