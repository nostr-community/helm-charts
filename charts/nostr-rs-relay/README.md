# nostr-rs-relay

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.8.13](https://img.shields.io/badge/AppVersion-0.8.13-informational?style=flat-square)

A Helm chart for Kubernetes to deploy the nostr-rs-relay application

This helm chart is maintained and released by the nostr-community on a best effort basis.

**Homepage:** <https://github.com/scsibug/nostr-rs-relay/tags>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| nourspace | <info@nour.space> |  |

## Source Code

* <https://github.com/nostr-community/helm-charts>
* <https://github.com/scsibug/nostr-rs-relay>

## Requirements

Kubernetes: `>=1.19.0-0`

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"scsibug/nostr-rs-relay"` |  |
| image.tag | string | `""` |  |
| ingress.className | string | `""` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"relay.domain.com"` |  |
| ingress.path | string | `"/"` |  |
| ingress.pathType | string | `"ImplementationSpecific"` |  |
| nameOverride | string | `""` |  |
| namespaceOverride | string | `""` |  |
| service.port | int | `8080` |  |
| service.targetPort | int | `8080` |  |
| service.type | string | `"ClusterIP"` |  |
