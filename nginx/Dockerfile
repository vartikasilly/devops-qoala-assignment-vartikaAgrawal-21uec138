FROM nginx:latest

# Copy nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static files
COPY ./html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]