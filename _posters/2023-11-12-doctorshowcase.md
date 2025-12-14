---
title: "Overcoming the Gap Between Compute and Memory Bandwidth in Modern GPUs"
collection: posters
permalink: /posters/2023-11-12-doctorshowcase
excerpt: 
date: 2023-11-12~17
venue: 'SC 23: Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis'
paperurl: 'http://lingqizhang.github.io/files/Poster_SC23_Poster_DoctorShowCase.pdf'
citation: 'Lingqi Zhang, Mohamed Wahib, Toshio Endo and Satoshi Matsuoka, "Overcoming the Gap Between Compute and Memory Bandwidth in Modern GPUs," In The International Conference for High Performance Computing, Networking, Storage and Analysis (SC ’23), November 12–17, 2023,
Denver, CO, USA.'
author_profile: false
---

The imbalance between the computational speed of a processor and memory bandwidth was identified two decades ago. Plenty of architectural research has been undertaken to mitigate this issue. Nevertheless, the gap between compute and memory bandwidth continues to widen. As a result, many workloads are bound by memory instead of by compute. Such workloads are classified as memory-bound kernels, and numerous efforts have been expended to optimize these kernels. This dissertation also centers on memory-bound kernels, with a particular emphasis on Graphics Processing Units (GPUs). In this dissertation, based on the observations of the latest GPU developments, we present strategies for overcoming the imbalance in compute and memory bandwidth. Specifically, we propose to extend the lifetime of the kernel across the time steps and take advantage of the large volume of on-chip resources (i.e., register files and scratchpad memory) in \textit{reducing} or \textit{eliminating} traffic to the device memory. Furthermore, we champion a minimum level of parallelism to maximize the available on-chip resources, maximizing the impact of the first strategy.

<!-- Parallel computing techniques have been introduced into digital image correlation (DIC) in recent years and leads to a surge in computation speed. The graphics processing unit (GPU)-based parallel computing demonstrated a surprising effect on accelerating the iterative subpixel DIC, compared with CPU-based parallel computing. In this paper, the performances of the two kinds of parallel computing techniques are compared for the previously proposed path-independent DIC method, in which the initial guess for the inverse compositional Gauss-Newton (IC-GN) algorithm at each point of interest (POI) is estimated through the fast Fourier transform-based cross-correlation (FFT-CC) algorithm. Based on the performance evaluation, a heterogeneous parallel computing (HPC) model is proposed with hybrid mode of parallelisms in order to combine the computing power of GPU and multicore CPU. A scheme of trial computation test is developed to optimize the configuration of the HPC model on a specific computer. The proposed HPC model shows excellent performance on a middle-end desktop computer for real-time subpixel DIC with high resolution of more than 10000 POIs per frame.
citation: 'Lingqi Zhang, Mohamed Wahib, Toshio Endo and Satoshi Matsuoka, "Overcoming the Gap Between Compute and Memory Bandwidth in Modern GPUs," In The International Conference for High Performance Computing, Networking, Storage and Analysis (SC ’23), November 12–17, 2023,
-->
