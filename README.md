# superkart-project7-final
superkart detail

## Run with Docker Compose

Start the frontend and prediction API with:

```sh
docker compose up --build
```

Open <http://localhost:8501>. The frontend connects to the backend over the
Compose network. When running the frontend outside Compose, set `BACKEND_URL`
to the address where the backend API is reachable.
