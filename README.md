# kubernetes_ref
Reference yaml files for kubernetes learning

## For cloud deployement
- replace webapp NodePort with LoadBalancer and remove "targetPort" from ports. Only keep port:80

## Usefule links:
### Getting external traffic into kubernetes cluster
- https://www.udemy.com/course/kubernetes-microservices/learn/lecture/11157308
- https://www.ovh.com/blog/getting-external-traffic-into-kubernetes-clusterip-nodeport-loadbalancer-and-ingress/
- https://medium.com/google-cloud/kubernetes-nodeport-vs-loadbalancer-vs-ingress-when-should-i-use-what-922f010849e0

### EFK stack on DigitalOcean K8S
- https://www.digitalocean.com/community/tutorials/how-to-set-up-an-elasticsearch-fluentd-and-kibana-efk-logging-stack-on-kubernetes
