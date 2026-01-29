# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 43c23cfc4b21ce7717c053e934dc6a9a2dc1e0ce
helm template . --name-template prod-helm-guestbook --include-crds
```
