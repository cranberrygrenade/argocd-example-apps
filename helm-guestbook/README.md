# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 0b44cfd17474d2ce069fafee605bf0e1f009f572
helm template . --name-template test-helm-guestbook --include-crds
```
