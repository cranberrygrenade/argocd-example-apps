# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 2f20cf9e53a5bdaf3637ad771e2ca94ca40a2fd2
helm template . --name-template test-helm-guestbook --include-crds
```
