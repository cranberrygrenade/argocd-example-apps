# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 0148bb84bce2076f2fce28bad2885179661495f3
helm template . --name-template prod-helm-guestbook --include-crds
```
