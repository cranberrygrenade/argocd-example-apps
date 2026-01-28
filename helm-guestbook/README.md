# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 68502df44b82ddf3328ebce3c5c8d2fb64f9496b
helm template . --name-template test-helm-guestbook --include-crds
```
