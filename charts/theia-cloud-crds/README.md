# theia-cloud-crds

![Version: 0.11.0-next.1](https://img.shields.io/badge/Version-0.11.0--next.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.11.0-next](https://img.shields.io/badge/AppVersion-0.11.0--next-informational?style=flat-square)

A Helm chart for the custom resource definitions (CRDs) of Theia Cloud

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| clusterIssuer | string | `"theia-cloud-selfsigned-issuer"` | The cluster issuer to use for the certificate |
| conversion.certMountPath | string | `"/etc/webhook/certs"` | The location of where the certificates are mounted into the container (needs to match with application.properties) |
| conversion.image | string | `"theiacloud/theia-cloud-conversion-webhook:0.11.0-next"` | The image of the webhook container |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.12.0](https://github.com/norwoodj/helm-docs/releases/v1.12.0)
