# image-mirror

把公司内网拉不到的公共镜像（registry.k8s.io、docker.io 等）复制到 `ghcr.io/gl-game-group/mirror/*`。

在 `images.txt` 加一行并推送到 `main` 即触发复制；每周一也会自动刷新一次。镜像为 public，集群无需拉取凭据。
