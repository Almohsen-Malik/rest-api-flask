# CONTRIBUTING

## How to run Dockerfile locally

```
build:
sudo docker build -t rest_api_flask .

run:
sudo docker run -p 5000:5000 -w /app -v "$(pwd):/app" rest_api_flask sh -c "flask run"
```
