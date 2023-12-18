**metric-server On Kubernetes v1.21+:**

kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/high-availability-1.21+.yaml

**command to add load on a pod:**

whiletrue; do wget -qO- http://ip:port; done
