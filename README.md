## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```shell
helm repo add raghu-manne https://raghu-manne.github.io/helm-repo-gh-pages
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
raghu-manne` to see the charts.

To install the this chart:

    helm install my-release raghu-manne/my-release

To uninstall the chart:

    helm uninstall my-release