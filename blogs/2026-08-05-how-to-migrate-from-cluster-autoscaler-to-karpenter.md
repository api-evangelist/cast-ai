---
title: "How to Migrate from Cluster Autoscaler to Karpenter"
url: "https://cast.ai/blog/cluster-autoscaler-to-karpenter-migration/"
date: "2026-08-05"
author: "Kunal Das"
feed_url: "https://cast.ai/blog/feed/"
---
Migrating from Cluster Autoscaler to Karpenter means replacing managed node groups with Karpenter NodePools that provision nodes just in time. The migration is incremental: install Karpenter alongside Cluster Autoscaler, map your node groups to NodePools, shift workloads, then remove the old groups, with a clear rollback path at each step. The post How to Migrate from Cluster Autoscaler to Karpenter appeared first on Cast AI .
