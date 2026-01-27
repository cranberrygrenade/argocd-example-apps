# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout fe99f9e43daeaa876f460f1b5063f493f832542e
helm template . --name-template prod-helm-guestbook --include-crds
```
