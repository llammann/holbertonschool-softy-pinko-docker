# Use the latest official Nginx image as the base image
FROM nginx:latest

# Copy the front-end application files to the appropriate directory in the container
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Replace the default Nginx configuration with a custom configuration
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

