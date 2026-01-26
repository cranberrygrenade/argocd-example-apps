# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 398e07614a43fa68cc0c0c5973c5bf6dea6aeadc
helm template . --name-template prod-helm-guestbook --include-crds
```
