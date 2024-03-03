# test3


cd test3/cluster/flux-system
kubectl kustomize . | kubectl apply -f -
k get gitrepository,kustomization -n flux-system 