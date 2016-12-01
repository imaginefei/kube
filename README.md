# kube
由于不能从google container上直接pull镜像，所以这里通过docker hub的Automated Builds功能从项目的dockerfile中Build到docker的官方服务器上，然后再从它们上面拉取.

## 镜像地址:
```
gcr.io/google_containers/kubedns-amd64                   1.8
gcr.io/google_containers/kube-dnsmasq-amd64              1.4
gcr.io/google_containers/exechealthz-amd64               1.4
gcr.io/google_containers/pause-amd64                     3.0
gcr.io/google_containers/kubernetes-dashboard-amd64      v1.4.1
```
