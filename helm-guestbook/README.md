# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout e2ab11ddf88bb352b7abbaff50109cec0ddefe8e
helm template . --name-template prod-helm-guestbook --include-crds
```
