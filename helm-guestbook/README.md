# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout f24fc5cc5aff976829ff9d392762c2f6449fc78e
helm template . --name-template test-helm-guestbook --include-crds
```
