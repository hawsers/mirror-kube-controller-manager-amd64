# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kube-controller-manager-amd64:${VERSION}
docker tag hawsers/kube-controller-manager-amd64:${VERSION} k8s.gcr.io/kube-controller-manager-amd64:${VERSION}
docker rmi hawsers/kube-controller-manager-amd64:${VERSION}
```
