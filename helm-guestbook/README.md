# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 53240f24a5ba306ed0501fa0fe0b01ba2128019c
helm template . --name-template test-helm-guestbook --include-crds
```
