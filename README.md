# React Docker

An experiment in using Docker with React.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

To run the container using the Nginx setup, follow these steps:

1) docker build .
2) Copy the ID created for the image at the end of the build process
3) docker run -p 4000:80 ID
4) App should be running on localhost:8080