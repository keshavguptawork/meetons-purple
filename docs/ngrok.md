## MeetONS P2P - Ngrok

If you want to expose MeetONS from your `Local PC` to outside in `HTTPS`, you need to do 1 thing

Edit the Ngrok part on `.env` file

```bash
# 1. Goto https://ngrok.com
# 2. Get started for free
# 3. Copy YourNgrokAuthToken: https://dashboard.ngrok.com/get-started/your-authtoken

NGROK_ENABLED=true
NGROK_AUTH_TOKEN=2PKFSekQSZKwTHsufObLxEjnEfX_2Yw9xVx6xECoMVM4MQcmK
```

---

Then, when you run it with `npm start`, you should see in the console log this line:

```bash
server_tunnel: 'https://xxxxxxxxxxxxxxxxxx.ngrok.io'
```

So open it in your browser, join in the room, share it to whom you want and wait participants to join.

---
