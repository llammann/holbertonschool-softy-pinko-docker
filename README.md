# Softy Pinko Docker Project

> ## Overview

This project demonstrates the use of Docker to containerize a full-stack application, involving both front-end and back-end services. It provides practical experience in setting up, deploying, and scaling an application using Docker containers and Docker Compose. The project also covers essential topics like reverse proxy setup and load balancing to distribute traffic efficiently across multiple servers.

> ## Project Structure

### `Task 0: Building the Initial Docker Image`

- **Directory**: task0
- **Goal**: Create a basic Docker image using Ubuntu, update the system packages, and ensure the image outputs "Hello, World!" when run.

### `Task 1: Setting Up the Back-End`

- **Directory**: task1
- **Goal**: Construct a Docker image that installs Python3, pip3, and Flask. The Flask server will serve a simple "Hello, World!" message on a designated endpoint.

### `Task 2: Configuring the Front-End`

- **Directory**: task2
- **Goal**: Use Nginx to host static content for the front-end. Nginx will be configured to serve files from the Softy Pinko front-end project.

### `Task 3: Integrating Front-End with Back-End`

- **Directory**: task3
- **Goal**: Connect the front-end to the back-end API to display dynamic content. Implement CORS in the Flask application and modify the front-end to fetch data from the back-end.

### `Task 4: Simplification with Docker Compose`

- **Directory**: task4
- **Goal**: Manage multiple containers with Docker Compose. Define services for the front-end, back-end, and proxy in a `docker-compose.yml` file.

### `Task 5: Implementing a Proxy Server`

- **Directory**: task5
- **Goal**: Set up Nginx as a reverse proxy server to handle routing between the front-end and back-end. All traffic will pass through this proxy server.

### `Task 6: Scaling the Application`

- **Directory**: task6
- **Goal**: Achieve horizontal scaling by running multiple instances of the API server. Configure Nginx to distribute traffic evenly across these instances using a load-balancing strategy.

> ## Technologies Utilized

- **`Docker`**: For containerizing the application components.
- **`Docker Compose`**: For managing multi-container applications.
- **`Nginx`**: As a web server and reverse proxy.
- **`Flask (Python)`**: For developing the back-end API.

> ## Authors

*For questions or feedback, please feel free to reach the authors via the contact information provided:* <br>

`Laman Nazirli` <br>
* Email - lemannazirli8@gmail.com <br>
* Github - @llammann <br>
---

