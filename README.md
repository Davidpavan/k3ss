# k3ss
cd k3d-lab
k3d cluster create --config k3d.yaml
kubectl get nodes

kubectl apply --filename k8s/

k3d cluster create k3d-zelar(optinal name)

kubectl get nodes

1. etcd
2. kube-api-server
3. kube-scheduler
4  kube-controller[replications & node controller]
5. kubelet - common option which we can find on wrker and master node

3.control plane and master plane