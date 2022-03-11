# To build the dev Dockerfile

docker build -f Dockerfile.dev .

# To run the created container using volumes

docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app {IMG_ID}