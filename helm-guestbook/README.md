
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout e5987a1d760c40299daf2704115a713d15d8385e
helm template . --name-template guestbook --include-crds
```