# fluxcd-helm-chart
Shared helm chart


# Testing
```
helm template prod-secret-store ./generic-app --debug

//Render yaml to a file
helm template prod-secret-store ./generic-app > rendered.yaml
```