
---

## **File Descriptions**

### `frontend-deployment.yaml`
Deployment manifest for the frontend (Vite dev server) container. Configured with replicas, environment variables, and resource limits.

### `backend-deployment.yaml`
Deployment manifest for the backend (Node.js API) container. Includes environment variables, ConfigMap/Secret references, and resource limits.

### `mongo-deployment.yaml`
Deployment for MongoDB with an optional Persistent Volume Claim (PVC) for data persistence.

### `mongo-express-deployment.yaml`
Deployment for Mongo Express admin panel. Configured to connect to the MongoDB service using environment variables.

### `ingress.yaml`
Ingress resource exposing frontend to browser with host/path-based routing. Optional rule for Mongo Express subdomain.

