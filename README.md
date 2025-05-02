# SimpleLogin YunoHost App (Docker-based)

This is a YunoHost package for self-hosting [SimpleLogin](https://simplelogin.io) via Docker.

## Features
- Docker-based deployment with PostgreSQL & Redis
- Secure automatic setup of admin account
- HTTP to HTTPS redirection via NGINX

## Installation
```bash
yunohost app install https://github.com/YOUR_USERNAME/simplelogin_ynh
```

## Requirements
- YunoHost with Docker installed

## Notes
- Admin credentials are generated during install and shown in the final message
- This app is intended for low to moderate use with custom domains

## Maintainer
Your Name (<you@example.com>)
