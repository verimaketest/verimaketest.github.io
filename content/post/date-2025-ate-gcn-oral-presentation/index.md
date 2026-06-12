---
title: "Bruno da Silva and Ruiqi Chen attend DATE'25 with an oral presentation on ATE-GCN"
date: 2025-04-02
authors:
  - ruiqi-chen
  - bruno-da-silva
tags:
  - DATE 2025
  - Conference
  - EDA
  - FPGA
  - Graph Neural Networks
image:
  focal_point: Smart
  preview_only: false
---

Bruno da Silva and Ruiqi Chen attended the 2025 Design, Automation and Test in Europe Conference (DATE'25), where Ruiqi delivered an oral presentation of [ATE-GCN: An FPGA-Based Graph Convolutional Network Accelerator with Asymmetrical Ternary Quantization](https://verimaketest.github.io/publication/chen-2025-ate/).

DATE is one of the top-tier conferences in electronic design automation (EDA), with nearly 2,000 submissions and an acceptance rate of only about 20% in 2025. This presentation marks the first DATE oral presentation from VUB ETRO with VUB as both the first affiliation and corresponding affiliation.

The paper introduces ATE-GCN, an FPGA-based accelerator for graph convolutional networks (GCNs). Existing ternary quantization can greatly simplify neural-network matrix multiplication, but the paper shows that applying conventional symmetric ternary quantization directly to GCNs can cause severe accuracy loss because GCN weights follow a bimodal distribution. ATE-GCN addresses this with an asymmetrical ternary quantization strategy tailored to GCN weights, together with a software-hardware co-optimized FPGA architecture. On the hardware side, ATE-GCN uses a unified processing-element array that supports both ternary computation and sparse matrix multiplication, while exploiting FPGA cascade structures and DSP resources for high throughput. Implemented on a Xilinx VCU118 FPGA board, the prototype keeps accuracy loss below 2%, achieves average speedups of 224.13x over CPU and 11.1x over GPU, and improves DSP efficiency by 63% compared with state-of-the-art FPGA-based GCN accelerators.
