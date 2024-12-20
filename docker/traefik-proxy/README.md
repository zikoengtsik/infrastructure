# Traefik Proxy

Traefik Proxy is a reverse proxy that can be used to route requests to different services based on the request's host or path.

## Features

- User-friendly dashboard.
- Automatic discovery of services using Docker.
- Enable HTTP/3 support.
- Automatic SSL certificate generation using Let's Encrypt.

## Usage

1. Copy the directory `traefik-proxy` to your root directory.
2. Copy `.env.example` to `.env`, and modify the values.
3. Run command `docker network create ingress-traefik` to create network for Traefik Proxy.
4. Run command `docker compose up -d` to start Traefik Proxy.

## TLS

### ACME with Let's Encrypt

Refer to the [official documentation](https://doc.traefik.io/traefik/https/acme/) for more information.

## Middleware

### Basic Auth

Refer to the [official documentation](https://doc.traefik.io/traefik/middlewares/http/basicauth/) for more information.
