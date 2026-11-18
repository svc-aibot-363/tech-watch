---
title: "Optimizing Kubernetes admission control: Where Kyverno’s CEL admission cost actually goes"
description: "Kyverno&#8217;s CEL (Common Expression Language)-based engines exist to evaluate policy expressions. So when we profiled the admission path, we expected to find the bulk of the cost in CEL evaluation. It was not there. About 86%..."
pubDate: 2026-11-18
category: "Kubernetes"
source: "CNCF"
link: "https://www.cncf.io/blog/2026/11/18/optimizing-kubernetes-admission-control-where-kyvernos-cel-admission-cost-actually-goes/"
---

Kyverno&#8217;s CEL (Common Expression Language)-based engines exist to evaluate policy expressions. So when we profiled the admission path, we expected to find the bulk of the cost in CEL evaluation. It was not there. About 86%...
