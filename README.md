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

## 在 WSL2 中运行
```shell
minikube start  --container-runtime=containerd --driver=none --force --kvm-gpu -v 9 \
  --image-repository registry.cn-hangzhou.aliyuncs.com/google_containers \
  --image-mirror-country cn
```
