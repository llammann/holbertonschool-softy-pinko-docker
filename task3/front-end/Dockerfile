# Use the latest version of the Nginx image from Docker Hub
FROM nginx:latest

# Copy the front-end files from the local directory to the Nginx web root directory
# This will make the front-end application available at the root of the Nginx server
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the custom Nginx configuration file to the Nginx configuration directory
# This will override the default configuration with your custom settings
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

