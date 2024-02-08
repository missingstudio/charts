## Missing studio helm chart
🌈 Missing studio is an open-source [AI studio](https://www.missing.studio) for rapid development and robust deployment of generative AI applications. This repository contains Helm chart to deploy AI Studio and its components on a kubernetes cluster.

## TL;DR
```sh
$ helm repo add missingstudio https://missingstudio.github.io/charts/
$ helm search repo missingstudio
$ helm install studio missingstudio/studio
```

## Usage
Once you have installed the Helm client on your kubernetes cluster, you can deploy a Missing studio Helm Chart into a Kubernetes cluster.

Please refer to the [Quick Start](https://helm.sh/docs/intro/quickstart) guide if you wish to get running in just a few commands, otherwise the Using [Helm Guide](https://helm.sh/docs/intro/using_helm) provides detailed instructions on how to use the Helm client to manage packages on your Kubernetes cluster.

Helm Repo URL: `https://missingstudio.github.io/charts/`

## 🫶 Contributions
Missing studio is an open-source project, and contributions are welcome. If you want to contribute, you can create new features, fix bugs, or improve the infrastructure. 

It's still very early days for this so your mileage will vary here and lots of things will break. But almost any contribution will be beneficial at this point. Check the [current Issues](https://github.com/missingstudio/charts/issues) to see where you can jump in!

## License
AI Studio is [Apache 2.0](https://github.com/missingstudio/studio/blob/main/LICENSE) licensed.