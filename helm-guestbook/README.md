# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout e1d90103f14554974eafbf62661ee47f29b981d4
helm template . --name-template prod-helm-guestbook --include-crds
```
