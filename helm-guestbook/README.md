# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout c0ea063f291dd3b6fc04780449080f312fb97c8b
helm template . --name-template prod-helm-guestbook --include-crds
```
