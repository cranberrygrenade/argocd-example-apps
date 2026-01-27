# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 1be0c6676730f64224c9c58a6071fdcbfe9c9acd
helm template . --name-template prod-helm-guestbook --include-crds
```
