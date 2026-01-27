# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 08d94f9cd81ff2246a4569cc7ccc584bfc4e3db8
helm template . --name-template prod-helm-guestbook --include-crds
```
