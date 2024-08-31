# Use the latest version of the Ubuntu image from Docker Hub
FROM ubuntu:latest

# Update package lists and upgrade installed packages
RUN apt-get update && apt-get upgrade -y

# Install Python 3 and pip3
RUN apt-get install -y python3 python3-pip

# Remove EXTERNALLY-MANAGED file to avoid issues with pip installations
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

# Install Flask and Flask-CORS Python packages
RUN pip3 install flask flask-cors

# Set the working directory to /app
WORKDIR /app

# Copy the api.py file into the working directory
COPY api.py /app/api.py

# Expose port 5252 for the application
EXPOSE 5252

# Run the api.py script using Python 3
CMD ["python3", "api.py"]

