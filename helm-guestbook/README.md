# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout aae8883bbefec05eda04e5fa431585ff7751d7ee
helm template . --name-template prod-helm-guestbook --include-crds
```
