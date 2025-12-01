
<p align="center">
 <img src="docs/assets/kronicle-icon-removebg-preview.png" alt="drawing" width="200"/>
</p>


# Kronicle
> ChatOps Monitoring for Kubernetes Deployments

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/kronicle)](https://artifacthub.io/packages/helm/kronicle/kronicle)

![Python Version](https://img.shields.io/badge/dynamic/regex?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbensoer%2Fkronicle%2Frefs%2Fheads%2Fmain%2F.python-version&search=.*&logo=python&logoColor=blue&label=python&color=yellow)
![Latest Container](https://img.shields.io/github/v/release/bensoer/kronicle?sort=semver&filter=v*&logo=docker&label=Latest%20Container&color=blue)
![Latest Chart](https://img.shields.io/github/v/release/bensoer/kronicle?sort=semver&filter=!v&logo=helm&label=Latest%20Chart&color=green&logoColor=green)


Kronicle allows you to enable/disable event changes of a service, during a deployment, from slack!

# Setup


# Configuration


# Developer Notes
Install development onto minikube by running:

```bash
helm upgrade --install kronicle charts/kronicle --set image.tag=main --set image.pullPolicy=Always
```