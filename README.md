# DL-UPM : Guide to Run the app on Docker

#### Prerequisites
- **Docker Installed**: Ensure Docker is installed on your machine. [Download and install Docker here](https://www.docker.com/products/docker-desktop/).
- **Dockerfile in the Project Directory**: Make sure your project folder contains a `Dockerfile`.

### Steps

1. `cd /path/to/your/project`
2. `docker build -t name_of_the_app .`
3. `docker run -p 8501:8501 name_of_the_app`
