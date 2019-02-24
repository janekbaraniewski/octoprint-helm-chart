# Octoprint Helm Chart

Helm chart I used for [Octoprint](https://octoprint.org/)  
Based on [nunofgs/octoprint](https://hub.docker.com/r/nunofgs/octoprint/) image  

## TL;DR;
Clone/download this repo, then
```bash
$ cd octoprint-helm-chart
$ helm install --name octoprint .
```

## Configuration

|         Parameter          |                Description                 |                   Default                   |
|----------------------------|--------------------------------------------|---------------------------------------------|
| `image.repository`                    | octoprint image repository                            | `nunofgs/octoprint`                   |
| `image.tag`          | image tag | `1.3.10-arm32v7`                              |
| `image.pullPolicy`      | Image pull policy | `IfNotPresent`                                      |
| `service.type`         | Service type                        | `NodePort`                                       |
| `service.port`                | Port |`80`                |

For more check values.yaml
