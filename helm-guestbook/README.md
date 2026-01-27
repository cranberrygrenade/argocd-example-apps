# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout bd07c0f23fd724d9bd05d5e64968534514bd3cce
helm template . --name-template test-helm-guestbook --include-crds
```
