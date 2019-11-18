# Octoprint Helm Chart

Helm chart I used for [Octoprint](https://octoprint.org/)

## TL;DR;
Clone/download this repo, then
```bash
$ cd octoprint-helm-chart
$ helm install --name octoprint .
```

## Configuration

|         Parameter          |                Description                 |                   Default                   |
|----------------------------|--------------------------------------------|---------------------------------------------|
| `image.repository`                    | octoprint image repository                            | `janekbaraniewski/octoprint`                   |
| `image.tag`          | image tag | `1.3.10`                              |
| `image.pullPolicy`      | Image pull policy | `IfNotPresent`                                      |
| `printer.enabled`                | Enable socat connection to printer |`false`                |
| `printer.host`                | Printer host |``                |
| `printer.port`                | Printer port |`3333`                |
| `ingress.enabled`         | Enable ingress                        | `false`                                       |
| `service.type`         | Service type                        | `ClusterIP`                                       |
| `service.port`                | Port |`80`                |


For more check values.yaml
