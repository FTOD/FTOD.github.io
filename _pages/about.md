---
layout: about
title: about
permalink: /
subtitle: ARTIC Fellow @ <a href='https://www.comp.nus.edu.sg/'> School of Computing, National University of Singapore</a>

profile:
  align: right
  image: photo.jpg
  image_circular: false # crops the image to make it circular
  more_info:

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

*Moore's Law is over; memory is the enemy.*  
*Don't repeat the VLIW mistake: compiler–hardware co-design is the key to making dataflow architectures the winner.*


My current research focuses on dataflow architecture and compilers. We develop CGRA-style dataflow architectures and polyhedral-based compilation for systems with explicit data movement, distributed memories, and parallel compute units.

On the software side, we build compiler support for tile-based DSLs (e.g., Triton and Helion) targeting commercial dataflow platforms, including Tenstorrent, IBM AIU, AMD NPU/AIE and classical NPU/TPU-like architectures. Our prototype end-to-end flow (Helion/Triton → MLIR → TT-Metal) on Tenstorrent Wormhole achieves performance comparable to vendor libraries on tensor kernels and fused AI operators.