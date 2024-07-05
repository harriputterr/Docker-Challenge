FROM nginx:latest

# Copy the custom nginx.conf to the appropriate location in the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the entire public directory to the NGINX html directory
COPY public /usr/share/nginx/html/

# Expose port 8080
EXPOSE 8080
 