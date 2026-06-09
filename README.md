# Setting up a Local Development Environment with Docker

## Objective

The goal of this task is to understand Docker containerization by creating and running a simple Python Flask application inside a Docker container.

## Project Structure

* app.py
* requirements.txt
* Dockerfile

## Docker Commands Used

### Build Docker Image

```bash
docker build -t flask-app .
```

### Run Docker Container

```bash
docker run -p 5000:5000 flask-app
```

## Expected Output

Open the browser and visit:

```text
http://localhost:5000
```

Output:

```text
Hello from Docker!
```

## What I Learned

* Basics of Docker containers
* Creating a Dockerfile
* Building Docker images
* Running containers locally
* Benefits of application containerization

## Challenges Faced

Initially, understanding Docker images, containers, and Dockerfile instructions was challenging. After creating and studying the Docker workflow, I gained a better understanding of containerized application deployment.
