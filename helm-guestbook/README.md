# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 39acbc25cb80fea974fc87cde00f5de214706fc6
helm template . --name-template test-helm-guestbook --include-crds
```
