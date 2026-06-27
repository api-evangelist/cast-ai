---
title: "OOMKilled and Exit Code 137: Why Kubernetes Kills Your Pods and How to Stop It"
url: "https://cast.ai/blog/oomkilled-exit-code-137/"
date: "2026-06-26"
author: "Roberto Pesce"
feed_url: "https://cast.ai/blog/feed/"
---
Exit code 137 means your container was killed by SIGKILL (signal 9) — 128 + 9. The Linux kernel OOM killer fires SIGKILL when a container exceeds its cgroup memory limit. Kubernetes surfaces this as OOMKilled in pod status.
