---
title: "Kubernetes Node NotReady: Why Nodes Go NotReady and How to Fix It"
url: "https://cast.ai/blog/kubernetes-node-not-ready/"
date: "2026-07-23"
author: "Kunal Das"
feed_url: "https://cast.ai/blog/feed/"
---
A Kubernetes node in NotReady state has stopped reporting healthy to the control plane, so it cannot run new pods and may evict existing ones. Causes include a failed or stopped kubelet, network or CNI problems, resource pressure (memory, disk, PID), or a cloud instance issue. This guide diagnoses and fixes each.
