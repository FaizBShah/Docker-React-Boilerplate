# Docker React Boilerplate

This project is a sample boilerplate to use a React app with Docker. Supports hot-reloading in the docker-container.

## Setup Instructions

### Build the docker image

To build the image, run:
```
make build-image
```

### Start the development server

To start the server, run:
```
npm run dev
```

The server will then start running on port 3000

### Note:

When adding some new package, or making changes to the `package.json` file, re-build the image and restart the server