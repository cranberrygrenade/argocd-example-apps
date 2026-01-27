# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cranberrygrenade/argocd-example-apps
# cd into the cloned directory
git checkout c07817c0a074bad6cd77ec08e29987c623d00ec2
helm template . --name-template prod-helm-guestbook --include-crds
```
