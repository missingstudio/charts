## Missing studio core chart
🌈 Missing studio is an open-source [AI studio](https://www.missing.studio) for rapid development and robust deployment of generative AI applications. This repository contains a core generic Helm chart to deploy AI Studio.

## TL;DR
```sh
$ helm install [RELEASE_NAME] .
```
## Example for Installing an application

To install the chart with the release name `RELEASE_NAME` and image `studio`:

```bash
$ helm install --name RELEASE_NAME . -f ./path-to/values.yaml --set image.repository=missingstack/studio --set image.tag=latest --set ingress.enabled=true

```

The command deploys missingstack/studio on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete tghe `RELEASE_NAME` deployment:

```bash
$ helm delete [RELEASE_NAME]
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
