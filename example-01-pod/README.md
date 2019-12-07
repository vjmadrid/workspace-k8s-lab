# example-01-pod

Execute the following command

```bash
kubectl run acme-greeting-api-restful-k8s --image=acme/acme-greeting-api-restful-k8s:lastest --port=8091
```

kubectl run --generator=run-pod/v1 --dry-run --image=acme/acme-greeting-api-restful-k8s:latest acme-greeting-api-restful-k8s -o yaml >> acme-greeting-api-restful-k8s-pod.yaml

kubectl run --generator=run-pod/v1 --image=acme/acme-greeting-api-restful-k8s:latest acme-greeting-api-restful-k8s

kubectl run acme-greeting-api-restful-k8s --image=acme/acme-greeting-api-restful-k8s:latest --port=8091


kubectl run kubernetes-first-app --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080

## Authors

* **Víctor Madrid**
