# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 94590407d4475f66851cf650ee2fd935dfa09d0a
helm template . --name-template test-helm-guestbook --include-crds
```
