---
layout: page
title: Canon
description: A parallel dataflow architecture for irregular kernels
img: assets/img/canon.png
importance: 1
category: work
---

Canon is a parallel dataflow architecture that targets accelerator-class efficiency without sacrificing programmability, especially for data-dependent irregular kernels such as sparse tensor operations.

Canon follows a two-tier execution model: compile-time scheduling exploits workload regularity, while lightweight runtime orchestration handles irregularity. Compiler-programmed FSM orchestrators translate input meta-data (e.g., sparse coordinates) into control instructions on the fly.

To reduce control overhead, Canon employs time-lapsed SIMD with staggered instruction propagation across the PE array, enabling an evolving dataflow. Overall, Canon delivers high performance across both data-agnostic and data-driven kernels with efficiency comparable to specialized accelerators.