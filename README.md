# kind-calico

### Install Kind Cluster ( on Linux )

```bash
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.18.0/kind-linux-amd64
chmod +x ./kind
sudo mv ./kind /usr/local/bin
```

### Install Calico

```bash
kubectl apply -f https://projectcalico.docs.tigera.io/manifests/calico.yaml
```
