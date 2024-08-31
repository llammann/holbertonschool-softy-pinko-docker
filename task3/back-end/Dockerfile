FROM ubuntu:latest

# Update & upgrade the system
RUN apt-get update && apt-get upgrade -y

# Install Python and pip
RUN apt-get install -y python3 python3-pip

# Remove the EXTERNALLY-MANAGED file if it exists (this may not always be necessary)
RUN rm -f /usr/lib/python*/EXTERNALLY-MANAGED

# Install necessary Python packages
RUN pip3 install flask flask-cors

# Set the working directory
WORKDIR /app

# Copy the application code to the container
COPY api.py /app/api.py

# Define the command to run the application
CMD ["python3", "api.py"]

