
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/coquinncecg/argo-hydrate.git
# cd into the cloned directory
git checkout a92db683edc645fd2c6cb339f503b1fbaf0d27ba
helm template . --name-template guestbook --include-crds
```