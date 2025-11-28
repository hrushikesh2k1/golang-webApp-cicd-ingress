Developer team reached out to us and say implement DevOps part for this Go application.

## steps we follow

1. Containerizing the application using Docker by writing Docker file.
2. We create kubernetes manifests like Deployment, Service, Ingress.
3. We implement CI using GitHub Actions.
4. We implement CD using GitOps tool(Argocd).
5. We also setup kubernetes cluster (AKS).
6. We also setup Helm charts for application deployments (Dev, Stage, Prod).
7. We also setup ingress controller configuration for exposing application to outside world.
8. Mapping LB IP address to DNS to see application working.
