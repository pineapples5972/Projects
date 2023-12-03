# README
This is the simple container to host a static webpage into nginx container using docker or podman.

## Installation
- Clone the repo
  `git clone https://github.com/pineapples5972/Projects && cd Projects/Simple-Nginx-Container`
- Build the Image
  `docker build -t nginx:test .`
## Usage
- Run the container
  `docker run -d -p 5051:80 nginx:test`
