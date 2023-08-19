# Helm Chart Repository

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add cert-manager-webhook-oci https://thpham.github.io/cert-manager-webhook-oci
> helm repo update
> helm repo list
NAME URL
cert-manager-webhook-oci https://thpham.github.io/cert-manager-webhook-oci
> helm search repo -l cert-manager-webhook-oci/
NAME                                                    CHART VERSION   APP VERSION     DESCRIPTION
cert-manager-webhook-oci/cert-manager-webhook-oci       1.0             1.11.2          Allow cert-manager to solve DNS challenges using Oracle Cloud Infrastructure DNS
```

You can then run `helm search repo cert-manager-webhook-oci` to see the charts.

## Contributing

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
We'd love to have you contribute! Please refer to our [contribution guidelines](https://github.com/thpham/cert-manager-webhook-oci/blob/main/CONTRIBUTING.md) for details.

## Helm chart build status

![Release Helm Chart](https://github.com/thpham/cert-manager-webhook-oci/workflows/Release%20Helm%20Chart/badge.svg?branch=main)
