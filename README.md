Installed with https://k3s.io/


SSH:

```
ssh root@88.99.227.214
```

Open Dashboard:
```
export KUBECONFIG=./kubeconfig.yml
kubectl --kubeconfig ./kubeconfig.yml proxy


./dashboard-token.sh

# OPEN http://localhost:8001/
```


