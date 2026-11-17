---
title: "Scheduling the removal of the kube-proxy IPVS backend"
description: "The ipvs backend for kube-proxy was an experiment in providing a service proxy implementation with better performance than the iptables backend. While it succeeded in that goal, the kernel IPVS API has turned out to be a bad match for the Kubernetes Services API, and the ipvs backend was never able "
pubDate: 2026-11-16
category: "Kubernetes"
source: "Kubernetes Blog"
link: "https://kubernetes.io/blog/2026/11/16/ipvs-removal/"
---

The ipvs backend for kube-proxy was an experiment in providing a service proxy implementation with better performance than the iptables backend. While it succeeded in that goal, the kernel IPVS API has turned out to be a bad match for the Kubernetes Services API, and the ipvs backend was never able 
