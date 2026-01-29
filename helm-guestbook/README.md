# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout c60d82dfb54c1dad33db08fdcd9532d94e5f0573
helm template . --name-template prod-helm-guestbook --include-crds
```
