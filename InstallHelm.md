# Visit the page
```xml
https://helm.sh/docs/intro/install/
```

# Go to the /usr/local/bin directory (or another directory in your PATH)
```xml
cd /usr/local/bin
```

**Helm Chart3**
```xml
curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash
```
**Add Helm Repositories**
```xml
helm repo add stable https://charts.helm.sh/stable
```
Update the repositories to get the latest charts:
```xml
helm repo update
```

# Install a Helm Chart
You can install a chart on your Kubernetes cluster. For example, to install nginx using Helm:
```xml
helm install my-nginx stable/nginx-ingress
```

Check the Release Status
```xml
helm list
```
