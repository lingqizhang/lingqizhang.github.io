---
title: "Can Tensor Cores Benefit Memory-Bound Kernels? (NO!)"
collection: workshop
permalink: /publication/2025-03-01-tensorcore
excerpt: #'Theoretical and empirical analysis of tensor cores on memory-bound kernels'
date: 2025-03-01
venue: 'GPGPU 25: Proceedings of the 17th Workshop on General Purpose Processing Using GPU'
paperurl: 'https://dl.acm.org/doi/10.1145/3725798.3725803'
citation: 'Lingqi Zhang, Jiajun Huang, Sheng Di, Satoshi Matsuoka, and Mohamed Wahib. 2025. Can Tensor Cores Benefit Memory-Bound Kernels? (NO!). In Proceedings of the 17th Workshop on General Purpose Processing Using GPU (GPGPU 25). Association for Computing Machinery, New York, NY, USA. https://doi.org/10.1145/3725798.3725803.'
author_profile: false
---

Tensor cores are specialized processing units within GPUs that have demonstrated significant efficiency gains in compute-bound applications such as Deep Learning Training by accelerating dense matrix operations. Recent studies have reported that tensor cores can outperform traditional CUDA cores even on memory-bound kernels. In this work, we challenge these findings through both theoretical and empirical analysis. Our theoretical analysis reveals that tensor cores can achieve a maximum speedup of only 1.33x over CUDA cores for memory-bound kernels in double precision (for V100, A100, and H100 GPUs). We validate this theoretical limit through empirical analysis of three representative memory-bound kernels: STREAM Scale, SpMV, and stencil. Our results demonstrate that optimizing memory-bound kernels using tensor cores does not yield sound performance improvements over CUDA cores.
