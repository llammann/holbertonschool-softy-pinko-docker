# Use the latest version of Ubuntu as the base image
FROM ubuntu:latest

# Update the package list and upgrade installed packages
RUN apt-get update && apt-get upgrade -y

# Install Python3 and pip3
RUN apt-get install -y python3 python3-pip

# Remove the EXTERNALLY-MANAGED file if necessary
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED || true

# Install Flask using pip3
RUN pip3 install flask

# Set the working directory
WORKDIR /app

# Copy the api.py file to the Docker image
COPY ./api.py /app/api.py

# Expose port 5252 for the Flask app
EXPOSE 5252

# Command to run the Flask application
CMD ["python3", "api.py"]

