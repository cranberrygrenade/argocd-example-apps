# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout e9cf0b4a8c31b088b324226b1085afc1a5ccedfa
helm template . --name-template prod-helm-guestbook --include-crds
```
