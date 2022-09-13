# docker-node-example

Used [this tutorial](https://www.geeksforgeeks.org/docker-docker-container-for-node-js/) from GFG

Build docker container with 
`docker build -t docker-container-nodejs .`

Run container with 
`docker run -d -p 8000:3000 -v address_to_app_locally:/app docker-container-nodejs`
