# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 65b3f7380bb234fe480a6a953bc9fd69c609a3bb
helm template . --name-template test-helm-guestbook --include-crds
```
