# Credmark Helm Chart Repository

Repo for hosting [Helm](https://helm.sh) charts.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```{bash}
helm repo add credmark [https://credmark.github.io/helm-charts](https://credmark.github.io/helm-charts)
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
credmark` to see the charts.

To install the <chart-name> chart:

```{bash}
helm install my-<chart-name> credmark/<chart-name>
```

To uninstall the chart:

```{bash}
helm delete my-<chart-name>
```