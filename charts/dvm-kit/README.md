# nostr-rs-relay

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: latest](https://img.shields.io/badge/AppVersion-latest-informational?style=flat-square)

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
| dvms | object | `{}` |  |
| dvms_list[0] | string | `"dvm_echo.Echo"` |  |
| env.NOSTR_ADMIN | string | `"nsec"` |  |
| env.NOSTR_RELAYS | string | `"wss://dev-relay.kube.b-n.space"` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"nourspace/dvm-kit"` |  |
| image.tag | string | `""` |  |
| nameOverride | string | `""` |  |
| namespaceOverride | string | `""` |  |
