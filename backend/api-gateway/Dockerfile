# Use the official NGINX image as the base image
FROM nginx

# Copy the NGINX configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the API gateway configuration file to the container
COPY api-gateway.conf /etc/nginx/conf.d/api-gateway.conf

# Expose port 80 for incoming HTTP traffic
EXPOSE 80
