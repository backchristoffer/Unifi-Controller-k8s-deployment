# Unifi-Controller-k8s-deployment
Deploys unifi-controller on a k8s/k3s cluster with nodeport service to expose the unifi-controller

# NodePort information
The nodeports used are 8443:32321 and 8080:32322

# How to deploy
$ kubectl apply -f https://raw.githubusercontent.com/backchristoffer/Unifi-Controller-k8s-deployment/main/unifi_controller.yaml -n < namespace >
