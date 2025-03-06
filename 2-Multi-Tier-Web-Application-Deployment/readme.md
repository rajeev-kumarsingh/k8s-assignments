# Assignment : Multi-Tier Web Application Deployment

Objective: Deploy a multi-tier web application using proper configurations.

Task:
Deploy frontend (nginx:latest) and backend (node:18) as separate Deployments.
The frontend should:
Pass the backend URL as an environment variable (BACKEND_URL=http://backend-service:5000).
Expose port 80.
The backend should:
Request 200m CPU, 256Mi memory.
Limit 500m CPU, 512Mi memory.
Expose port 5000.
Define Services for inter-component communication.
Use labels to organize resources (app: frontend and app: backend).

---

Questions:

What QoS class was assigned to each pod?
How does QoS affect scheduling and eviction?
What happens when a node is under resource pressure?
