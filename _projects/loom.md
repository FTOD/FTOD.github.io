---
layout: page
title: Loom
description: An end-to-end compiler for spatial dataflow accelerators
img: assets/img/loom.png
importance: 2
category: work
---
TL is an end-to-end compiler framework for spatial dataflow accelerators. It compiles tile-based programs into efficient multi-core executions by deciding grid-to-core placement, temporal scheduling, and explicit data movement across the on-chip network and distributed memories.

TL explores spatiotemporal mappings and data-movement plans, ranks candidates with a hardware-aware performance model, and profiles a small top-k set to select the final mapping. A key enabler is a portable hardware representation (topology, memories, compute) that supports diverse spatial dataflow targets.

On Tenstorrent Wormhole, TL matches or outperforms vendor libraries on GEMM and FlashAttention kernels.