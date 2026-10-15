# Basic Dockerfile

A simple Docker project that demonstrates how to build and run a Docker image using a custom Dockerfile.

This project is part of the [roadmap.sh Basic Dockerfile project](https://roadmap.sh/projects/basic-dockerfile).

## Requirements

- Docker installed and running.
- Base image: `alpine:latest`.

## Project Structure

```text
basic-dockerfile/
├── Dockerfile
└── README.md
```

## Build the Image

```bash
docker build -t basic-dockerfile .
```

## Run the Container

```bash
docker run --rm basic-dockerfile
```

Expected output:

```text
Hello, Captain!
```

## Learning Outcomes

- Understanding Dockerfiles and base images.
- Building a Docker image.
- Running a container and executing a command.
- Using `--rm` to automatically remove a container after it exits.
