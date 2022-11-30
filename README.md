# elasticsearch-docker-mirror

This is elasticsearch docker image mirror, because access to oficial elasticsearch image is restricted for Russia and Belarus.

Pull latest image:
```console
$ docker pull ghcr.io/hirotasoshu/elasticsearch 
```

Pull by tag:
```console
$ docker pull ghcr.io/hirotasoshu/elasticsearch:7.17.7 
```
Use as a base image in Dockerfile:
```console
FROM ghcr.io/hirotasoshu/elasticsearch 
```

