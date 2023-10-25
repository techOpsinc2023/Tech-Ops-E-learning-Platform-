# Use an official nginx runtime as a parent image
FROM nginx:latest

# Set the working directory to /app
WORKDIR /app

# Copy the nginx configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the static files to the container
COPY static /app/static

# Expose port 80 for incoming traffic
EXPOSE 80

# Start nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
