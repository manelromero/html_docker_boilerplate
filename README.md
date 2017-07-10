## Basic HTML page with Docker

### Installation
- Clone or download this repository into your directory
- In your app directory, run `docker build -t <your_image_name> .` to build your Docker image

### Run the application
- Run your Docker container with `docker run --rm --name <your_container_name> -p 8080:80 <your_image_name>`
- Open [http://localhost:8080](http://localhost:8080) in your browser and you should see the **HTML page boilerplate** header
