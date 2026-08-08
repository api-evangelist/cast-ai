---
title: "Karpenter and Spot Instances: Cut Compute Cost Without Gambling on Reliability"
url: "https://cast.ai/blog/karpenter-spot-instances/"
date: "2026-08-05"
author: "Leon Kuperman"
feed_url: "https://cast.ai/blog/feed/"
---
Karpenter can provision Spot Instances by setting the capacity type in a NodePool, which cuts compute cost sharply. The risk is interruption, so the pattern is to diversify instance types, handle the spot interruption signal gracefully, and fall back to on-demand when spot is unavailable, returning to spot when capacity stabilizes. The post Karpenter and Spot Instances: Cut Compute Cost Without Gambling on Reliability appeared first on Cast AI .
