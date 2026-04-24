---
layout: page
title: S-SONDO
description: Self-supervised knowledge distillation for tiny audio foundation models. 61x compression, 96.4% performance. Accepted at ICASSP 2026.
img:
importance: 1
category: research
---

**S-SONDO: Self-Supervised Knowledge Distillation for General Audio Foundation Models**

First-author paper accepted at **ICASSP 2026**, co-authored with Aurian Quelennec, Pierre Chouteau, Geoffroy Peeters, and Slim Essid at Telecom Paris (ADASP Group).

### Highlights

- Implemented and benchmarked **state-of-the-art audio encoders** for large-scale foundation model pretraining
- Leveraged **multi-GPU (NVIDIA A100) distributed training** for high-throughput experiments
- Built and optimized high-throughput data workflows for the **AudioSet dataset** (~2M samples, 650-700 GB)
- Designed a **self-supervised distillation framework** in PyTorch & Lightning
- Delivered the **most efficient tiny audio foundation model to date**: **61x model compression** with **96.4% performance retention**

### Tech Stack

PyTorch, PyTorch Lightning, HuggingFace, NVIDIA A100 GPUs, distributed training
