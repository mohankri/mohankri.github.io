---
title: Scaling GPU Clusters to 10,000 Nodes
date: 2026-03-07
---

Modern AI models require large-scale GPU clusters.  
Distributed training is enabled via:

- Pipeline Parallelism

Example command:

```bash
python train.py --tensor-parallel 8 --nodes 128
