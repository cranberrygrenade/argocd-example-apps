# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout 0b6260849e4e3a7ea89dd0d654cb81cac5defcfc
helm template . --name-template test-helm-guestbook --include-crds
```
