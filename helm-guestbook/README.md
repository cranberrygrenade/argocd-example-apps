# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout a96080f6201eab230d00d3be3c37ec4db4da88eb
helm template . --name-template test-helm-guestbook --include-crds
```
