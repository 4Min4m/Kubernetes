# Kubernetes
Mastering kubectl
Mastering kubectl! 🌐⚙️

A thread explaining 20 imp kubectl commands with brief explanations 👇

What is kubectl?

kubectl is a command-line tool used for interacting with Kubernetes clusters.

It serves as the primary interface for administrators, developers, and DevOps engineers to interact with Kubernetes clusters.

Here are 20 kubectl commands with brief explanations 👇

1/20 🔍 Get cluster info:

💡 Command: 
kubectl cluster-info 

Explanation: View Kubernetes cluster details like API server address and cluster services.

2/20 🗂️ List all pods in default namespace:

💡 Command: 
kubectl get pods 

Explanation: Get a list of all running pods in the default namespace.

3/20 🔄 Watch pods in real-time:

💡 Command: 
kubectl get pods -w 

Explanation: Watch pods and receive updates as they change status in real-time.

4/20 ➕ Create a new deployment:

💡 Command: 
kubectl create deployment my-deployment --image=my-image:latest 

Explanation: Launch a new deployment using the specified image.

5/20➡️ Expose deployment as a service:

 💡 Command: 
kubectl expose deployment my-deployment --port=80 --type=LoadBalancer 

Explanation: Create a service to expose the deployment on port 80 using a LoadBalancer.

6/20 🔄 Scale a deployment:

💡 Command: 
kubectl scale deployment my-deployment --replicas=3 

Explanation: Change the number of replicas for the deployment to 3.

7/20 🗑️ Delete a resource:

💡 Command: 
kubectl delete pod my-pod 

Explanation: Delete a specific pod by name.

8/20🗄️ List all services:

 💡 Command: 
kubectl get services 

Explanation: View all running services in the cluster.

9/20 📝 Show pod logs:

💡 Command: 
kubectl logs my-pod 

Explanation: Display logs from a specific pod.

10/20 🔄 Stream pod logs:

💡 Command: 
kubectl logs -f my-pod 

Explanation: Stream logs from a specific pod continuously.

11/20 🔒 Show pod details with labels:

💡 Command: 
kubectl get pods -L app 

Explanation: Display pods with their corresponding 'app' labels.

12/20 🔍 Describe a resource:

💡 Command: 
kubectl describe pod my-pod 

Explanation: Get detailed information about a specific pod.

13/20 🗂️ List all namespaces:

💡 Command: 
kubectl get namespaces 

14/20 🔄 Switch namespace context:

💡 Command: 
kubectl config set-context --current --namespace=my-namespace

15/20 📁 Create a YAML file for a resource:

💡 Command: 
kubectl create deployment my-deployment --image=my-image:latest --dry-run=client -o yaml > deployment.yaml

16/20 ✨ Apply YAML manifest:

kubectl apply -f deployment.yaml

17/20 🛠️ Edit a resource:

kubectl edit deployment my-deployment

18/20 🔄 Update a resource using YAML:

kubectl apply -f updated-deployment.yaml

19/20 🔄 Rollout status of deployment:

kubectl rollout status deployment/my-deployment

20/20 🔄 Rollback deployment:

kubectl rollout undo deployment/my-deployment

Happy #Kubernetes-ing! 🚀 Let me know if you need more commands or assistance! 😊

#Kubernetes #DevOps #Linux #Automation
