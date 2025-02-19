# Default Helm-Values

TrueCharts is primarily build to supply TrueNAS SCALE Apps.
However, we also supply all Apps as standard Helm-Charts. In this document we aim to document the default values in our values.yaml file.

Most of our Apps also consume our "common" Helm Chart.
If this is the case, this means that all values.yaml values are set to the common chart values.yaml by default. This values.yaml file will only contain values that deviate from the common chart.
You will, however, be able to use all values referenced in the common chart here, besides the values listed in this document.

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| env.TS3SERVER_LICENSE | string | `"accept"` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"teamspeak"` |  |
| image.tag | string | `"3.13.6@sha256:a88d61887cbfa78012ce8bf69e6fad5988d853b7b72a9483000b1af8a6083ff8"` |  |
| persistence.config.accessMode | string | `"ReadWriteOnce"` |  |
| persistence.config.enabled | bool | `true` |  |
| persistence.config.mountPath | string | `"/var/ts3server/"` |  |
| persistence.config.size | string | `"100Gi"` |  |
| persistence.config.type | string | `"pvc"` |  |
| podSecurityContext.runAsGroup | int | `0` |  |
| podSecurityContext.runAsUser | int | `0` |  |
| securityContext.readOnlyRootFilesystem | bool | `false` |  |
| securityContext.runAsNonRoot | bool | `false` |  |
| service.files.enabled | bool | `true` |  |
| service.files.ports.files.enabled | bool | `true` |  |
| service.files.ports.files.port | int | `30033` |  |
| service.files.ports.files.protocol | string | `"TCP"` |  |
| service.files.ports.files.targetPort | int | `30033` |  |
| service.files.type | string | `"ClusterIP"` |  |
| service.main.enabled | bool | `true` |  |
| service.main.ports.main.enabled | bool | `true` |  |
| service.main.ports.main.port | int | `10011` |  |
| service.main.ports.main.protocol | string | `"TCP"` |  |
| service.main.ports.main.targetPort | int | `10011` |  |
| service.main.type | string | `"ClusterIP"` |  |
| service.voice.enabled | bool | `true` |  |
| service.voice.ports.voice.enabled | bool | `true` |  |
| service.voice.ports.voice.port | int | `9987` |  |
| service.voice.ports.voice.protocol | string | `"UDP"` |  |
| service.voice.ports.voice.targetPort | int | `9987` |  |

All Rights Reserved - The TrueCharts Project
