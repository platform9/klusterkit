# klusterkit
Toolkit to simplify Kubernetes deployments and operations on on-prem, air-gapped environments

## Introduction

Klusterkit is composed of three independent tools, that can be used separately, or in tandem to orchestrate the lifecycle of a production-grade Kubernetes cluster:

![Klusterkit Architecture](https://platform9.com/wp-content/uploads/2019/04/klusterkit-architecture-etcdadm-nodeadm-cctl.jpg)

* [etcdadm](https://github.com/kubernetes-sigs/etcdadm), a CLI that simplifies operating an etcd cluster
* [nodeadm](https://github.com/platform9/nodeadm), a CLI node administration tool that complements kubeadm by deploying the dependencies that kubeadm requires
* [cctl](https://github.com/platform9/cctl), a cluster lifecycle management tool that adopts the Kubernetes community’s Cluster API and uses nodeadm and etcdadm to easily deploy and maintain highly-available Kubernetes clusters in on-premises, even air-gapped environments.

### For more information see [cctl](https://github.com/platform9/cctl) and [wiki](https://github.com/platform9/cctl/wiki)
