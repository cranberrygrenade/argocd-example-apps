# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout e7d43344288c6d777cb6f7b1141eed6a64f8533a
helm template . --name-template test-helm-guestbook --include-crds
```
