# To run the system use following command after changing current directory to project directory
bash-3.2$ 
bash-3.2$ kubectl apply -f k8s

# Use following command to get the IP of the minikube
bash-3.2$ minikube ip
<IP>

Use following in browser
http://<IP>


# To clean up the system use the following commands
bash-3.2$ 
bash-3.2$ kubectl delete deployments --all
bash-3.2$ 
bash-3.2$ kubectl delete services --all
bash-3.2$ 
bash-3.2$ kubectl delete pvc --all
bash-3.2$ 
bash-3.2$ kubectl delete ingress --all
bash-3.2$ 
