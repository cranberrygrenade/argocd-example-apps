# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 1efb815bc645eb10defbc2893a79230c63129bcb
helm template . --name-template test-helm-guestbook --include-crds
```
