---
contributor: rod
date: '2025-06-19T09:10:22.153253'
external_url: 'https://arxiv.org/html/2506.15993v1'
title: 'HetGPU: The pursuit of making binary compatibility towards GPUs'
image: ../../../static/images/news/2025-06-19-hetgpu-binary-compatibility.webp
pinned: false
tags:
  - sycl
---

Heterogeneous GPU infrastructures present a binary compatibility challenge: code 
compiled for one vendor’s GPU will not run on another due to divergent instruction sets, 
execution models, and driver stacks. This article proposes  hetGPU, a new system comprising 
a compiler, runtime, and abstraction layer that together enable a single GPU binary to execute 
on NVIDIA, AMD, Intel, and Tenstorrent hardware. Featuring SYCL. 
