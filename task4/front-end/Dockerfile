# Use the latest version of the Nginx image from Docker Hub
FROM nginx:latest

# Copy the front-end application files into the Nginx HTML directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the Nginx configuration file to the default configuration directory
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

