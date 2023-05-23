Docker Amazon Linux Systemd
=====================

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple tags that relate to Almalinux versions.

|Amazon Linux Version|Docker image tag   |
|--------------------|-------------------|
|2                   |2                  |
|2023 (latest)       |2023, latest       |

Manually starting
-----------------

```shell
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  mullholland/docker-amazonlinux-systemd
```
