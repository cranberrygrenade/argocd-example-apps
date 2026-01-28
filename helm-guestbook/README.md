# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 45ab58c21088b02032ee990b18d1528727c4f603
helm template . --name-template master-helm-guestbook --include-crds
```
