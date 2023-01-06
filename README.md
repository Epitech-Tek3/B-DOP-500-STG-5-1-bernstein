#K3D

start: k3d cluster start
stop: k3d cluster stop


#if you have a probleme whit:
command:
    - kubectl apply -f cadvisor.daemonset.yaml
      - error: "The connection to the server localhost:8080 was refused - did you specify the right host or port?"
    - Resolve:
      - use K3d not minicube

Use this for beter interpratation:
Nom : Kubernetes
ID : ms-kubernetes-tools.vscode-kubernetes-tools
Description : Develop, deploy and debug Kubernetes applications
Version : 1.3.3
Serveur de publication : Microsoft
Lien de la Place de marché pour VS : https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools
