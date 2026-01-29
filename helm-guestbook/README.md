# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 55ca6f8458b362f20de07dd32485ef82dc328898
helm template . --name-template prod-helm-guestbook --include-crds
```
