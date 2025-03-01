# rabbitmq

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A Helm chart for Kubernetes

**Homepage:** <https://github.com/NikolayMarusenko/rabbitmq>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| KubeRocketCI |  | <https://github.com/epam/edp-install/> |

## Source Code

* <https://github.com/NikolayMarusenko/rabbitmq>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| rabbitmqCluster.externalSecretName | string | `""` |  |
| rabbitmqCluster.ingress.annotations | object | `{}` |  |
| rabbitmqCluster.ingress.className | string | `""` |  |
| rabbitmqCluster.ingress.dnsWildcard | string | `"rabbitmq.example.com"` |  |
| rabbitmqCluster.ingress.enabled | bool | `false` |  |
| rabbitmqCluster.ingress.hosts[0].host | string | `""` |  |
| rabbitmqCluster.ingress.hosts[0].paths[0].path | string | `"/"` |  |
| rabbitmqCluster.ingress.hosts[0].paths[0].pathType | string | `"ImplementationSpecific"` |  |
| rabbitmqCluster.ingress.tls | list | `[]` |  |
| rabbitmqCluster.name | string | `"rabbitmq"` |  |
| rabbitmqCluster.persistence.storage | string | `"2Gi"` |  |
| rabbitmqCluster.replicas | int | `1` |  |
| rabbitmqCluster.resources.limits.cpu | string | `"500m"` |  |
| rabbitmqCluster.resources.limits.memory | string | `"512Mi"` |  |
| rabbitmqCluster.resources.requests.cpu | string | `"50m"` |  |
| rabbitmqCluster.resources.requests.memory | string | `"256Mi"` |  |
| rabbitmqCluster.service.type | string | `"ClusterIP"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.13.1](https://github.com/norwoodj/helm-docs/releases/v1.13.1)
