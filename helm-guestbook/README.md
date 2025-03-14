
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout be1d60b1b1be0ab94d08e442d7885670d78dc1ea
helm template . --name-template guestbook --include-crds
```