# Synology CSI Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add synology-csi https://djcopley.github.io/synology-csi

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
synology-csi` to see the charts.

To install the synology-csi chart:

    helm install synology-csi synology-csi/synology-csi

To uninstall the chart:

    helm uninstall synology-csi
