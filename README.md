# docker-demo
A simple experiment with Docker and Docker Compose

Launching Docker Compose will instantiate 3 containers:
- `web1`: a simple NodeJs "Hello world" application
- `web2`: another instance of the same application
- `rproxy`: a NGINX instance acting as reverse proxy and load balancer of the two application nodes
