FROM nginx:latest

# Copy your custom Nginx configuration file
COPY ./nginx.conf /etc/nginx/nginx.conf

# Expose port 8080 for Nginx
EXPOSE 8080

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]