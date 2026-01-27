# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 49e3d8b4831a04a5ec844a4799291cb62fa1a95a
helm template . --name-template prod-helm-guestbook --include-crds
```
