# DevOps Portfolio - Containerized Web Application

## Project Overview
A simple portfolio website demonstrating Docker containerization skills. This project showcases my ability to containerize applications and deploy them using industry-standard tools.

## Technologies Used
- Docker
- Nginx web server
- HTML/CSS
- Docker Hub

## Project Structure
```
devopsportfolio/
├── Dockerfile
├── index.html
├── style.css
└── README.md
```

## How to Run Locally

### Prerequisites
- Docker installed on your machine

### Steps
1. Pull the image from Docker Hub:
### run bash script
   docker pull davidokunade/devopsportfolio:v1
```

2. Run the container:
### run bash script
   docker run -d -p 8080:80 davidokunade/devopsportfolio:v1
```

3. Open your browser and visit:
```
   http://localhost:8080
```

## Docker Hub
Image available at: https://hub.docker.com/r/davidokunade/devopsportfolio

## What I Learned
- Docker fundamentals and containerization
- Writing Dockerfiles
- Building and running Docker containers
- Port mapping and container networking
- Pushing images to Docker Hub
- Documentation best practices

## Future Improvements
- Add CI/CD pipeline with GitHub Actions
- Deploy to cloud platform (AWS/Azure)
- Add monitoring and logging