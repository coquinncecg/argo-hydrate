
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout 47da50d87541e8def972d9ddc427f58b2c33efb6
helm template . --name-template guestbook --include-crds
```