<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"provider":{"google":{"client_id":"client-id","client_secret":"client-secret","email_addresses":["alan@example.com"],"scopes":["profile","email","https://www.googleapis.com/auth/userinfo.email"]}}}' \
https://api.ngrok.com/edges/https/edghts_2x59lB7vitfrXuc6Vhctu45Dxw7/routes/edghtsrt_2x59l8n5vYd9WJXvn7IGdT9L52Y/oauth
```
