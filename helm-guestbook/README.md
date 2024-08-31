
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jcy0308/argocd-example-apps.git
# cd into the cloned directory
git checkout d7927a27b4533926b7d86b5f249cd9ebe7625e90
helm template . --name-template hydrator-test --include-crds
```