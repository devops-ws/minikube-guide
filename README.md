# minikube-guide

## 安装
```shell
minikube start --image-mirror-country cn \
  --image-repository registry.cn-hangzhou.aliyuncs.com/google_containers \
  --container-runtime containerd
```

```shell
minikube start --force --kvm-gpu --image-mirror-country cn \
  --image-repository registry.cn-hangzhou.aliyuncs.com/google_containers
```
