# Minimal Flask Application

Minimal `flask` application using `poetry` for dependency management.

# Installation

- Create `nginx` and `app` environment files in [env](./env) and update
```
cp env/.nginx.env.example env/.nginx.env
cp env/.app.env.example env/.app.env
```
# Usage

- Start container 
```
docker-compose up --build
```
The application will run at `localhost` with TLS ([here](https://localhost:443))
