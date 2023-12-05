# nginx-docker-app2
Contenairize Node.js Application and put it behind a Nginx proxy server

What are we doing here?

We are creating a node.js application that just say hello world. We put the application in a container. 
Then we create a Dockerfile that will spin up a Nginx server
We configure the nginx server to be a proxy server and to listen on the port 80 and to forward traffic to the node.js application.
We are not using Nginx load balancer feature yet.

