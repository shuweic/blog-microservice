# blog microservice
**Welcome to shuwei's repo!**
* before run the project, make sure _node, docker and Kubernetes_ are installed
# Get Start
```
skaffold dev
// build and push all images to docker and kubernetes cluster
```
# whats include
* great microservice template
* event-driven microservices Async communication by emits events to event-bus, encourage each service to be 100% self-sufficient. Relatively easy to handle temporary downtime or new service creation.
* Easily scalable to add new features or services, with Kubernetes you can replicate multiple services and distribute traffic via load balancer and Ingress Controller.
* restful API with one-many relationship
* build with skaffold and nodemon for real-time updates during development.

