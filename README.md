# Flask Docker Demo

This is a simple Flask app running inside a Docker container.

## Run Locally
```bash
docker build -t flask-docker-demo .
docker run -p 5000:5000 flask-docker-demo
