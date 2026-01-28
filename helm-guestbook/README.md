# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 8f7810e713a8d5eb4d580fee73b10e162463efbb
helm template . --name-template prod-helm-guestbook --include-crds
```
