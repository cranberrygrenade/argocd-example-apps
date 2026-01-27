# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 82a85161ae2c676cd4769b01463639cf2c6efc32
helm template . --name-template prod-helm-guestbook --include-crds
```
