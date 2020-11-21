# multiple-react-app

Completely containerized multiple SPAs created by CRA with client-side routing accessible through an nginx gateway under different paths.

## Run

```
docker-compose up
```

The `home` SPA will be available at [http://localhost:8080/home](http://localhost:8080/)

The `product` SPA will be available at [http://localhost:8080/product](http://localhost:8080/product)

## Notes

The `docker-compose.yaml` is just for convenience and demonstration purposes, of course the containers should be build with the correct `PUBLIC_URL` argument and pushed to a registry by your CI.
