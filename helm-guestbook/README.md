# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 314d3af8c5ee5b6483d34e5f1010c8e9479b8040
helm template . --name-template test-helm-guestbook --include-crds
```
