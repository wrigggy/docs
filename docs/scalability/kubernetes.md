## Overview

## Setting up a cluster (Development)

### Minikube

### Microk8s

## Setting up a cluster (Production)

You will need to choose an appropriate method of deploying and maintaining a cluster, here is a (non exhaustive) list of options:

| Method      | Difficulty |
| ----------- | ------------------------------------ |
| Managed Kubernetes       | Easiest |
| Rancher (with infrastructure provider)       | Easy |
| Rancher (Custom)       | Easy-Medium |
| RKE       | ??? |
| Kubespray | ??? |
| Kubeadm | ??? |

### Managed Kubernetes

The process of provisioning nodes, deploying and maintaining clusters is entirely outsourced to an external service.

| Managed Kubernetes Service | Company      | Link |
| ---------------------------| -------------|------------|
| AKS                        | Microsoft    | <https://docs.microsoft.com/en-us/azure/aks/> |
| DOKS                       | Digital Ocean| <https://docs.microsoft.com/en-us/azure/aks/> |

Deploying a cluster this way is very simple, fast and with little pre-requisite knowledge. The downside is that you will be locked into using nodes provisioned by the respective company, which can lead to higher costs. These services may also charge additional fees (control pane, load balancers etc).

### Rancher

Rancher can effectively replace the functionality that a managed kubernetes services provides, in other words, it will provide a server that can provision nodes, deploy and maintain clusters.

At the cost of having to run and maintain your own rancher server, you can achieve a lot more flexibilty; You can provision almost any machine to be added as a node to your cluster, from multiple (any?) cloud providers and even bare-metal servers.

To get started with Rancher, you will first have to setup your own rancher server: <https://rancher.com/docs/rancher/v2.x/en/quick-start-guide/>

### Rancher (with infrastructure provider)

### Rancher (Custom)

## Interacting with your cluster

## Agones

## Launching Colyseus Servers

## Server Discovery

## Logging and metrics

## Redundancy
