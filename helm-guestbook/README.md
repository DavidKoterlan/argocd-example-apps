# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/DavidKoterlan/argocd-example-apps
# cd into the cloned directory
git checkout e467a3607634153bf9ade46301608586e78ef44f
helm template . --name-template staging-helm-guestbook --include-crds
```
