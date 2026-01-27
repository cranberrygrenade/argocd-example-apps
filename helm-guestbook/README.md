# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout dbc252db39ef8b2eec526b52bc203947b3ac03bd
helm template . --name-template prod-helm-guestbook --include-crds
```
