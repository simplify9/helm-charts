## Introduction 
This chart bootstraps a dotnet core project deployment on a Kubernetes cluster using the Helm package manager.

## Prerequisites
- Kubernetes 1.12+
- Helm 3.0+

## Adding Helm Repo

TBD


## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install my-release simplyworks/dotnetcoresimple
```

The command deploys dotnet core project on the Kubernetes cluster in the default configuration. The [Parameters](#parameters) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Parameters

The following table lists the configurable parameters of the dotnetcoresimple chart and their default values per section/component:

### Essential Parameters
| Parameter                 | Description                                          |
|---------------------------|------------------------------------------------------|
| `image.repository`        | Docker image registry with image name                |
| `imagePullSecrets.name`   | Docker registry pull secret name                     |
| `ingress.hosts`           | Ingress Hosts names as an array                      |
| `ingress.hosts`           | Ingress Hosts names as an array                      |
| `secrets.mysecret`        | Environment variables needed for the pod as an array | 



### All Parameters
| Parameter                 | Description                                     | Default                                                 |
|---------------------------|-------------------------------------------------|---------------------------------------------------------|
|                           |                                                 |                                                         |
|                           |                                                 |                                                         |