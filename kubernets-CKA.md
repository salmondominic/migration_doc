curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.11.1/kind-linux-amd64

curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.20.0/kind-linux-amd64

kubectl get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
nttZ2thW9JIm25f0
salmon@DESKTOP-9KOJOUG:~/argocd$

CKA

master nodes: master nodes are control plance node, which has the responsible to monitor the whole cluster using set of components
ETCD: its like a database, where cluster configuration & resource details stored
kube-scheduler >> 



worker nodes:
