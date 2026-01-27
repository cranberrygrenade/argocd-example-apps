# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 16c17261e6796152b5cd58055f1c0ba805e0b9d2
helm template . --name-template test-helm-guestbook --include-crds
```
