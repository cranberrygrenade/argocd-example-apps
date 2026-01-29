# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout f838a51705a007c1e8ee12cb6590ba2c788624e1
helm template . --name-template test-helm-guestbook --include-crds
```
