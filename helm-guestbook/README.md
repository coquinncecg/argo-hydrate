
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout 959cdfc35a9a2711f419a3d30989ee35a3f9e31e
helm template . --name-template guestbook --include-crds
```