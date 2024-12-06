# Steps to Set Up the Project

## Step 1: Build and Push Docker Images to Docker Hub for both frontend and backend 

Backend Service
Navigate to the backend project directory and Build the Docker image:

`docker build -t bhartineha/techdome-backend:latest .`

Push the image to Docker Hub:

`docker push bhartineha/techdome-backend:latest`

Fronetnd Service
Navigate to the frontend project directory and Build the Docker image:

`docker build -t bhartineha/techdome-frontend:latest .`

Push the image to Docker Hub:

`docker push bhartineha/techdome-frontend:latest`

## Step 2: Create a docker-compose.yml file for backend, frontend and mongodb containers.
(File is attached in the repo)

## Step 3: Run the Services
Start the containers using Docker Compose:

`docker-compose up -d`

Verify that all services are running:

`docker ps`


## Here is the snapshots as result:

<H1 align="center">
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot1.png" width=2000px></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot2.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot3.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot4.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot5.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot6.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot7.png" width=2000p></picture> <br>
  
  <picture><img src="https://github.com/neha-dev-dot/techdome/blob/dc8394db73c2414772ee83b1a7179afacb2923bf/Screenshot8.png" width=2000p></picture>

</H1>





