# helm

```sh
# Add repo
helm repo add <chart-name> <repo-url>
    
# Print yaml output from a remote helm project
helm template <any-name> --repo https://<example-project>.github.io/helm-charts

# Print yaml output from a helm project in your local machine
helm template <any-name> .
```
