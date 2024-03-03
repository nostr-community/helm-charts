# nsecbunkerd

![Version: 0.1.1](https://img.shields.io/badge/Version-0.1.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: latest](https://img.shields.io/badge/AppVersion-latest-informational?style=flat-square)

A Helm chart for Kubernetes to deploy the nsecbunkerd application

This helm chart is maintained and released by the nostr-community on a best effort basis.

**Homepage:** <https://github.com/kind-0/nsecbunkerd/tags>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| nourspace | <info@nour.space> |  |

## Source Code

* <https://github.com/nostr-community/helm-charts>
* <https://github.com/kind-0/nsecbunkerd>

## Requirements

Kubernetes: `>=1.19.0-0`

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| adminNPubs | list | `[]` |  |
| adminNSec | string | `"hex-nsec"` |  |
| adminRelays | list | `[]` |  |
| config_file | string | `"/app/data/nsecbunker.json"` |  |
| database_file | string | `"/app/data/nsecbunker.db"` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `"nourspace/nsecbunkerd"` |  |
| image.tag | string | `""` |  |
| ingress.className | string | `""` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"nsecbunker.domain.com"` |  |
| ingress.path | string | `"/"` |  |
| ingress.pathType | string | `"ImplementationSpecific"` |  |
| nameOverride | string | `""` |  |
| namespaceOverride | string | `""` |  |
| notifyAdminsOnBoot | bool | `true` |  |
| relays | list | `[]` |  |
| service.port | int | `3000` |  |
| service.targetPort | int | `3000` |  |
| service.type | string | `"ClusterIP"` |  |

