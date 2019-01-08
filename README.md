# Kubernetes cluster for Elastick Stack
## Clone to folder
git pull https://github.com/mast0910/kube-elk.git
## Usage
1. Have kubernetes and minikube installed on computer
2. Spin up elasticsearch using **kubectl apply -f elasticsearch.yaml**
3. Spin up kibana using **kubectl apply -f kibana.yaml**
4. Spin up filebeat using **kubectl apply -f filebeat.yaml**

## Access
You can now acces Kibana by typing **minikube service kibana**.
Kibana should pop up in your standard browser.
