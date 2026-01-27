# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout b6a6594901d6f8ccd73cfa3bceacbc3667d11171
helm template . --name-template test-helm-guestbook --include-crds
```
