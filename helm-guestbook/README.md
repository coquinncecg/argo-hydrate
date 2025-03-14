
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout 53d271cc21865de4b1f94bb7a79ac33a62db5d37
helm template . --name-template guestbook --include-crds
```