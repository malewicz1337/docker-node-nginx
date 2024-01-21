# Docker Node Nginx

This repository contains a setup for running a Node.js application behind an Nginx reverse proxy using Docker.

## Components

- **Nginx**
- **Node.js**

## Structure

- `nginx/Dockerfile`: Dockerfile for setting up Nginx. [View File](https://github.com/malewicz1337/docker-node-nginx/blob/main/nginx/Dockerfile)
- `server/Dockerfile`: Dockerfile for setting up the Node.js application. [View File](https://github.com/malewicz1337/docker-node-nginx/blob/main/server/Dockerfile)
- `server/package.json`: Package.json file for Node.js application dependencies. [View File](https://github.com/malewicz1337/docker-node-nginx/blob/main/server/package.json)

## Setup and Usage

### Building the Containers

```bash
docker-compose up --build
```

## License

This project is open source and available under the [MIT License](LICENSE).
