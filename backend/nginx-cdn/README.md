# nginx-cdn

nginx-cdn is a simple content delivery network (CDN) built using the nginx web server. It allows you to distribute your static assets (such as images, videos, and other files) across multiple servers, reducing the load on your main server and improving the performance of your website.

## Installation

To install nginx-cdn, follow these steps:

1. Install nginx on your server if it's not already installed.
2. Clone the nginx-cdn repository to your server.
3. Copy the `nginx.conf` file to your nginx configuration directory (usually `/etc/nginx`).
4. Edit the `nginx.conf` file to configure your CDN settings (see below).
5. Restart nginx to apply the changes.

## Configuration

The `nginx.conf` file contains the configuration settings for your CDN. Here are the main settings you'll need to configure:

- `server_name`: The domain name of your CDN.
- `root`: The root directory where your static assets are stored.
- `proxy_pass`: The URL of your main server where requests will be forwarded if the asset is not found on the CDN.
- `expires`: The amount of time (in seconds) that the CDN should cache the asset.

## Usage

To use the CDN, simply replace the URLs of your static assets with the URL of your CDN. For example, if your main server is `example.com` and your CDN domain is `cdn.example.com`, you would replace:
