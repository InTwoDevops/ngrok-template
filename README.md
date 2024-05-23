# Ngrok Template

This repository provides a simple template for setting up ngrok with Docker Compose.

## Getting Started

Update .env file: Replace NGROK_AUTHTOKEN=CHANGE_ME with your ngrok authentication token.

Start ngrok and website:

```bash
docker compose up
```

### Access website:

Visit http://localhost:80 in your web browser to access the website.

### Check ngrok URL:

Visit http://localhost:4040 in your web browser to access the ngrok dashboard and find the random URL provided for accessing your website remotely.


That's it! You're ready to use ngrok with your website. Enjoy! 🚀
