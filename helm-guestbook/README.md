# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout f9b5b42f5ff8e39767d3e7ef5e667f5cfb383be0
helm template . --name-template test-helm-guestbook --include-crds
```
