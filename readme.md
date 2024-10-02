# Ngrok with nginx - Quick Start Sample

This sample application shows how we can use ngrok with nginx to open our machine from outside
It accepts an incoming requests from a browser
This sample application is also capable of getting multiple concurrent requests, because nginx is reverse proxy, and we can configure backend and frontend.


## Prerequisites

- An Ngrok account . [Create an account for free](https://ngrok.com/). 
- Install ngrok. Instructions [here](https://ngrok.com/docs/getting-started/)
 


## Configuration

### Ngrok
1. Create Account 
 - Get Token [here](https://dashboard.ngrok.com/authtokens)
 - GET domain (url) [here](https://dashboard.ngrok.com/domains)

2. Configure ngrok/ngrok.yml
NGROK_AUTH_TOKEN
and
NGROK_URL

### Browser
- configure ModHeader to set header "ngrok-skip-browser-warning" and bypass ngrok webpage
