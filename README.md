# aks-argo-gitops

Create secrets in key vault first:
- cloudflare-api-key
- cloudflare-api-token

```bash
kubectl apply -k external-dns
```

```bash
kubectl apply -k argocd
```

Set public ip address in cloudflare to ingress controller load balancer ip.
