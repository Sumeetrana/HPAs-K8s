## Install metrics server in the cluster
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml

## Check the cpu and memory utilization for pods and clusters
k top nodes
k top pods
