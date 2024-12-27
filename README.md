# Hello Captain Docker Project

This project demonstrates how to create a simple Docker image that prints a greeting message to the console. The base image used is `alpine:latest`.

## Features

- Prints "Hello, Captain!" to the console.
- (Optional) Allows passing a name as an argument to print "Hello, [your name]!" instead.

## Getting Started

### Prerequisites

- Docker installed on your machine. You can download it from [Docker's official website](https://www.docker.com/get-started).

### Building the Docker Image

1. Clone this repository or create a directory for the project.
2. Create a file named `Dockerfile` in the root directory and add the following content:

   ```Dockerfile
   # Use the latest version of Alpine as the base image
   FROM alpine:latest

   # Set the command to run when the container starts
   CMD echo "Hello, Captain!"

https://roadmap.sh/projects/basic-dockerfile# basic-dockerfile
# basic-dockerfile
