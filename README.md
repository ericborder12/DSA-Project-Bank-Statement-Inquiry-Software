# DSA-Project-Bank-Statement-Inquiry-Software
Bank Statement Inquiry Software
Install Docker

You need to verify that Docker is installed properly by these command
    docker --version
    docker-compose --version

How to run the app
  Builds the Docker image and starts the container
  The app will be accessible at http://localhost:5000
    docker-compose up --build

  After the first time build, when you want to run again, using this command
    docker-compose up
