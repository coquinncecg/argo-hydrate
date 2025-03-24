
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout bfb157467f38814a2c90b266416fb42673e818b2
helm template . --name-template guestbook-int --include-crds
```