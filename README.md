# Postgres and Node.js configuration for Kubernetes (development environments).

Download the code and just change next files: 
 - inside `00-secrets.yaml` change the default values for your config
 - change app port and image inside `06-node-deployment.yaml`
 - change the port app inside `07-node-service`
 - inside `01-volume.yaml` change the storage capacity. default 1Gi
 - inside `01-volume.yaml` change the storage capacity default 1Gi, and the hostPath.

File `05-postgres-service-expose.yaml` is just a connection test.