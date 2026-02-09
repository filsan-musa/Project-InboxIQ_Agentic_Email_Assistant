# Slack API → IBM watsonx Orchestrate Connection Template

This project does **not** include credentials.  
Use this guide to configure Slack integration inside **IBM watsonx Orchestrate**.

---

## SLACK API DRAFT / LIVE CONNECTION (ON ORCHESTRATE)

- CONFIGURE CONNECTION

| Field | Value |
|------|------|
| **Server URL (optional)** | `https://slack.com/api` |
| **Token URL** | `https://slack.com/api/oauth.v2.access` |
| **Authorization URL** | `https://slack.com/oauth/v2/authorize` |
| **Scope (optional)** | `chat:write channels:read` |
| **Client ID** | *your_client_id_here* |
| **Client Secret** | *your_client_secret_here* |

- CREDENTIAL TYPE
```text
Member credentials
```

## SLACK API CONNECTION (ON CREDENTIALS)

### OAUTH & PERMISSIONS

- REDIRECT URLS: your_redirect_link
```text
your_redirect_link
```

---

- BOT TOKEN SCOPES: 

| Scope          | Purpose                |
|----------------|------------------------|
| `channels:read` | Read public channels   |
| `chat:write`    | Send messages          |
| `groups:read`   | Read private channels  |
| `im:write`      | Send direct messages   |
| `users:read`    | Look up users          |
