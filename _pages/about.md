---
layout: about
title: about
permalink: /
subtitle: ARTIC Fellow @ <a href='https://www.comp.nus.edu.sg/'> School of Computing, National University of Singapore</a>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

My research focuses on dataflow architectures and compiler systems. On the hardware side, we design CGRA-style dataflow architectures, from custom microarchitectures and tapeouts to end-to-end software stacks. On the compiler side, we develop compilation techniques for systems with explicit data movement, distributed memories, and parallel compute units.

A central goal of our work is to support tile-based DSLs such as Helion across both our in-house architectures and commercial platforms, including Tenstorrent, IBM AIU, AMD NPU/AIE, NPU/TPU-style architectures, as well as the new dataflow features of NVidia's GPUs. Our [**Loom**](https://github.com/ecolab-nus/loom) framework provides an end-to-end compilation flow (Helion → MLIR → TT-Metal) for Tenstorrent, achieving performance comparable to vendor libraries on tensor kernels and fused AI operators.
