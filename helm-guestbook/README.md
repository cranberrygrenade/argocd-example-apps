# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 838e6443f5ac9dd517ce8be930e53eec19e1c124
helm template . --name-template prod-helm-guestbook --include-crds
```
