# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 74481b9d50a83277a917cf08b8776ac5b0ee6b31
helm template . --name-template prod-helm-guestbook --include-crds
```
