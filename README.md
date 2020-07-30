# Simply Charts 
Simply charts is a library that includes helm charts that helps with deployments on a Kubernetes cluster using the Helm package manager.

## Prerequisites
- Kubernetes 1.12+
- Helm 3.0+

## Adding SimplyCharts Helm Repo

To add the Incubator charts for your local client, run helm repo add:
```console
helm repo add simplycharts https://charts.sf9.io
```


## Installing one of the charts

To install the chart with the release name `my-release`:

```console
helm install my-release simplyworks/chart-name
```

The command deploys dotnet core project on the Kubernetes cluster in the default configuration. The [Parameters](#parameters) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling a Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
