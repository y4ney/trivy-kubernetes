# trivy-kubernetes

[![GoDoc](https://godoc.org/github.com/aquasecurity/trivy-kubernetes?status.svg)](https://godoc.org/github.com/aquasecurity/trivy-kubernetes)
![Build](https://github.com/aquasecurity/trivy-kubernetes/workflows/Build/badge.svg)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/aquasecurity/trivy-kubernetes/blob/main/LICENSE)

Trivy Kubernetes 语言库.

支持 trivy <-> 用于资源扫描的kubernetes通信。

# Description

此Lib的目的是通过kubernetes上下文扩展 trivy 功能：

- 列出资源
- 运行k8s作业

# Documentation
请查看 `trivy` 文档，其中提供了详细的安装、配置和快速入门指南，可在[Trivy Kubernetes](https://aquasecurity.github.io/trivy/latest/docs/kubernetes/cli/scanning/)获得