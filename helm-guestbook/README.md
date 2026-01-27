# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout c7175d89ec1b575a40ef52943c3b494aa0f4004a
helm template . --name-template prod-helm-guestbook --include-crds
```
