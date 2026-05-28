# 项目介绍

- 本项目用于构建 Kubernetes `linux/loong64` 编译过程所需的基础镜像

- 用于构建以下 Docker `linux/loong64` 镜像（以 kubernetes v1.31.1 为例）：
    - `registry.k8s.io/build-image/go-runner:v2.4.0-go1.26.2-bookworm.0`
    - `registry.k8s.io/build-image/distroless-iptables:v0.9.1`
    - `registry.k8s.io/build-image/debian-base-loong64:bookworm-v1.0.6`

# 分支介绍

- 此处未介绍的分支，请勿关注

| 分支                         | [kubernetes/release](https://github.com/kubernetes/release) 标签 | [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) 标签 | 代码变更                                                                                                                             |
|----------------------------|----------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| v0.21.1-kubernetes-v1.31.1 | v0.21.1                                                        | v1.31.1                                                              | [v0.21.1...v0.21.1-kubernetes-v1.31.1](https://github.com/xuxiaowei-com-cn/release/compare/v0.21.1...v0.21.1-kubernetes-v1.31.1) |
