# Free DevOps CI/CD Project

A beginner-friendly DevOps project built with Docker, Nginx, Git, and GitHub Actions.

## Features

- Static website built with HTML and CSS
- Dockerized Nginx web server
- Custom Docker image
- Local container testing
- CI/CD automation using GitHub Actions (planned)

## Technologies

- Ubuntu Linux
- Git and GitHub
- Docker
- Nginx
- GitHub Actions

## Run Locally

Build the image:

```bash
sudo docker build -t free-devops-website:v1 .
```

Run the container:

```bash
sudo docker run -d --name devops-website-test -p 8080:80 free-devops-website:v1
```

Test the website:

```bash
curl -I http://localhost:8080
```

Expected result: `HTTP/1.1 200 OK`

## Author

Ashish Hooda

