# Kubernetes cluster for Elastick Stack
## Usage
1. Have kubernetes and minikube installed on computer
2. Spin up elasticsearch using **kubectl apply -f elasticsearch.yaml**
3. Spin up kibana using **kubectl apply -f kibana.yaml**
4. Spin up filebeat using **kubectl apply -f filebeat.yaml**

## Access
You can now acces Kibana by typing **minikube service kibana**.
Kibana should pop up in your standard browser.
