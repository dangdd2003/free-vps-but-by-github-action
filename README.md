# Github Action VPS

Open tunneling to github action vps with ngrok.

Require two secrets:

- `SSH_PUBLIC_KEY`: public key to connect to the server
- `NGROK_AUTH_TOKEN`: ngrok auth token (create new free account)

> [!WARNING]
> Github action server only runs for 30-45 minutes before killing tunneling task (end session), so this is just for fast testing
> deployment :D Do not abuse github action server to deploy or host anything, ban alert!
