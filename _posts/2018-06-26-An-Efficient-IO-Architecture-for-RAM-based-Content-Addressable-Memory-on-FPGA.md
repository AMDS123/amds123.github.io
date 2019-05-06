---
layout: post
title: "An Efficient I/O Architecture for RAM-based Content-Addressable Memory on FPGA"
date: 2018-06-26 23:53:44
categories: arXiv_CV
tags: arXiv_CV
author: Xuan-Thuan Nguyen, Trong-Thuc Hoang, Hong-Thu Nguyen, Katsumi Inoue, Cong-Kha Pham
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the impressive search rate of one key per clock cycle, the update stage of a random-access-memory-based content-addressable-memory (RAM-based CAM) always suffers high latency. Two primary causes of such latency include: (1) the compulsory erasing stage along with the writing stage and (2) the major difference in data width between the RAM-based CAM (e.g., 8-bit width) and the modern systems (e.g., 256-bit width). This brief, therefore, aims for an efficient input/output (I/O) architecture of RAM-based binary CAM (RCAM) for low-latency update. To achieve this goal, three techniques, namely centralized erase RAM, bit-sliced, and hierarchical-partitioning, are proposed to eliminate the latency of erasing stage, as well as to allow RCAM to exploit the bandwidth of modern systems effectively. Several RCAMs, whose data width ranges from 8 bits to 64 bits, were integrated into a 256-bit system for the evaluation. The experimental results in an Intel Arria V 5ASTFD5 FPGA prove that at 100 MHz, the proposed designs achieve at least 9.6 times higher I/O efficiency as compared to the traditional RCAM.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.02330](https://arxiv.org/abs/1804.02330)

##### PDF
[https://arxiv.org/pdf/1804.02330](https://arxiv.org/pdf/1804.02330)

