# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout b0d00b724166d84ba060e611056278ac8cb71115
helm template . --name-template prod-helm-guestbook --include-crds
```
