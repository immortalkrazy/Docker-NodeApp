# Docker-NodeApp

# Project Statement
Organization is using Cloud for one of their products. The project is in its initial stages, and 
the organization is ready with its frontend. However, it is taking about 4 hours of effort to push 
each update to its production environment, which is an obstacle for the release of the product. 
To resolve this issue, the team has decided to containerize their application to ease the 
deployment process.

# Tools used

***Docker*** - For containerizing the application \
***Swarm*** - To deploy the containerized application on the cluster of servers \
***Kubernetes*** - A alternative to Docker swarm

# Objectives

1.  • Build a Docker image from that application \
    • Research on how to deploy a NodeJS application \
    • Write a Dockerfile for it \
    • Use volumes if it requires persistent storage \
    • Expose it to the internet

2.  • Deploy it on a cluster of Docker swarm with the replica set \
    • Set up a swarm cluster and configure an overlay network for the application \
    • Create a service for the application and scale it up.

3.  •  Deploy the app in Kubernetes \
    • Deploy the application in a Kubernetes cluster \
    • Expose the application within the cluster using a service