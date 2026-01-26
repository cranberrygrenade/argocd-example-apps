# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout ebe536684c913900d4032e668926538df8cbe62e
helm template . --name-template staging-helm-guestbook --include-crds
```
