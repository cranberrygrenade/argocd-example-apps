# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout bfbac0361674e58ea603d9833cd86f3a3b607694
helm template . --name-template test-helm-guestbook --include-crds
```
