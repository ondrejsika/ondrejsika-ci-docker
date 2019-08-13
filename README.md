# ondrejsika/ci

    Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/ondrejsika-ci-docker

Docker image for my Gitlab CI jobs.


## Toolchain

- git
- docker client, docker compose, docker machine
- ssh client, sshpass
- sshx (alias for `sshpass -e ssh -o StrictHostKeyChecking=no $@`)
- curl, wget
- zip, unzip
- mcli (Minio client)
- kubectl, helm
- terraform, consul, vault


## Build

```
docker build -t ondrejsika/ci .
```

## Publish

```
docker push ondrejsika/ci
```

