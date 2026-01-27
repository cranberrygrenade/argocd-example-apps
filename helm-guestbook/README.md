# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout f0b1eebc4132360ef9eb6822308e7203eef48196
helm template . --name-template test-helm-guestbook --include-crds
```
