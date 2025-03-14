
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout 6c3cbe63dce5833c4729a381f5e349d8bc1043c6
helm template . --name-template guestbook --include-crds
```