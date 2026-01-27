# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 2dad04338a6a3bd3633f440fd6b33a824a09b1bf
helm template . --name-template test-helm-guestbook --include-crds
```
