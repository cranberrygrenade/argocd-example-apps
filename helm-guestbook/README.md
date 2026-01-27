# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout b437d44208c8030f552b11c9ea4e67de96e7a473
helm template . --name-template prod-helm-guestbook --include-crds
```
