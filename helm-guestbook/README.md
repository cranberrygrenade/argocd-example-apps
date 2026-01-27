# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 32dab4214c7480e0ac8fe31ea681569cbfd8e5cb
helm template . --name-template test-helm-guestbook --include-crds
```
