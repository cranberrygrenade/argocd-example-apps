# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 0e8e7edcd783ab6782d2b64bdf90f835668e1226
helm template . --name-template prod-helm-guestbook --include-crds
```
