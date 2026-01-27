# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 73521ef0f9ee1240f78fd4f38711c696275511e6
helm template . --name-template prod-helm-guestbook --include-crds
```
