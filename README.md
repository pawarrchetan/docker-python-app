# Overview
This repository contains source code for a sample conatinerized flask app.

# Details

The app exposes a simple falsk app on port 5000.
The `docker run` command can be used to bind port 5000 to the host port.

## Single-stage build

`docker run -itd -p 5000:5000 pawarrchetan/docker-python-app:v0.0.1`

## Multi-stage build

`docker run -itd -p 5000:5000 pawarrchetan/docker-python-app:multistage-v0.0.5`

# Development

## Prerequisites
* Install Docker desktop or Docker for Linux on your local system
* Python3.7 or higher

## Steps

1. Clone this repo to your local system.
`git clone https://github.com/pawarrchetan/docker-python-app.git`

2. Run the docker run command to start the container.
`docker run -itd -p 5000:5000 pawarrchetan/docker-python-app:multistage-v0.0.5`