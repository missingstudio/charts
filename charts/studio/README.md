## Missing studio core chart
🌈 Missing studio is an open-source [AI studio](https://www.missing.studio) for rapid development and robust deployment of generative AI applications. This repository contains a Helm chart for AI Studio.

## TL;DR
```sh
$ helm install [RELEASE_NAME] .
```
## Installing the Chart

### Install released version using Helm repository

- Add the missingstudio charts repo

```bash
$ helm repo add studio https://missingstudio.github.io/charts/
```

- Install it with Helm 3

```bash
$ helm install [RELEASE_NAME] missingstudio/studio
```

### Install development version using master branch

To install the chart with the release name `RELEASE_NAME`:

```bash
$ helm install --name RELEASE_NAME .

```

The command deploys missingstack/studio on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete tghe `RELEASE_NAME` deployment:

```bash
$ helm delete [RELEASE_NAME]
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
