# libcurl4-openssl-dev
Build Docker images for libcurl4-openssl-dev

## Build and Push 7.68.0-focal and latet images
```bash
docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 --tag richardrigby/libcurl4-openssl-dev:7.68.0-focal ./ubuntu/20.04 --push
docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 --tag richardrigby/libcurl4-openssl-dev:latest ./ubuntu/20.04 --push
```

## Build and Push 7.58.0-bionic image
```bash
docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 --tag richardrigby/libcurl4-openssl-dev:7.58.0-bionic ./ubuntu/18.04 --push
```