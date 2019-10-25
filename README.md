# OAE-hilary docker image

Docker container for CCI to run Hilary on

## Usage

### Run from dockerhub

```
docker run -it --name=oae-hilary --net=host oaeproject/oae-hilary
```

### Build the image locally

```
# Step 1: Build the image
docker build -f Dockerfile -t oae-hilary:latest .
# Step 2: Run the container
docker run -it --name=oae-hilary --net=host oae-hilary:latest
```
