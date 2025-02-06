# V2ray Server Setup with Nginx and SSL Configuration

This script automates the installation and configuration of a V2ray server with WebSocket (WS) support, Nginx as a reverse proxy, and SSL certification via Certbot.

## Prerequisites

- A fresh Ubuntu server or a server running Ubuntu 18.04 or later.
- A domain name for your server (needed for SSL certification).
- Root (sudo) access to the server.

## Features

- Installs and configures **V2ray** with WebSocket support.
- Sets up **Nginx** as a reverse proxy for V2ray.
- Automatically installs **SSL** using **Certbot** and configures HTTPS.
- Generates a unique UUID for the V2ray client.
- Provides a V2ray client configuration after setup.

## Setup Instructions

### 1. Clone the Repository

Clone this repository to your server:

````bash
git clone https://github.com/sachithdh/v2ray-automated-deploykit.git
cd v2ray-automated-deploykit


### 2. Run the Setup Script

Ensure the script is executable:

```bash
chmod +x setup

Then, execute the script to start the installation process:

./setup
````
