# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 7ca60ac523990482c70a15a4738bc92971fe7689
helm template . --name-template test-helm-guestbook --include-crds
```
