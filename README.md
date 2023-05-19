voting-app - Python

result-app - Node.js

in-memory db - Redis

db - Postgresql

worker - .NET

Containerized the above microservices in docker

Have used links when using the docker run to connect the microservices with each other as app is dependent on db

Created images of them pushed to DockerHub and deployed them Kubernetes using the respective manifest files written

Implemented the auto-scaling functionality using Deployments as a kind to the above setup
