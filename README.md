# Kubernetes-Cluster-with-MiniKube

Elevate Labs DevOps Internship Task 5

##Implementation
- Installed Minikube and provided $PATH to Windows Powershell and Git Bash. 
- Used Docker for Windows, to implement container runtime for minikube. 
- Enabled Minikube dashboard, and verified cluster and kubectl status.
- Created a sample Deployment.yaml and service.yaml to run nginx and create 3 replicate set containers for deployment. 
- Deployed Application, checked pod status, services running. 
- Ran kubectl scale deployment nginx-deployment --replicas=5 and --replicate=2 to scale up and down replica sets. 
- Checked The pods using kubernetes dashboard and "kubectl get pods"
- Looked into descibe deployments and logs using "kubectl descibe <podname>" and "kubectl logs <podname>"
