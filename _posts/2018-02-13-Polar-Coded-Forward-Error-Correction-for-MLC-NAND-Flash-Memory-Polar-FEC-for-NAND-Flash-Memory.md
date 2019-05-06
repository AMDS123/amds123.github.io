---
layout: post
title: "Polar-Coded Forward Error Correction for MLC NAND Flash Memory Polar FEC for NAND Flash Memory"
date: 2018-02-13 11:55:06
categories: arXiv_CV
tags: arXiv_CV
author: Haochuan Song (1 and 2 and 3), Frankie Fu (4), Cloud Zeng (4), Jin Sha (5), Zaichen Zhang (2 and 3), Xiaohu You (3), Chuan Zhang (1 and 2 and 3) ((1) Lab of Efficient Architectures for Digital-communication and Signal-processing (LEADS), (2) Quantum Information Center of Southeast University, (3) National Mobile Communications Research Laboratory, Southeast University, China, (4) Lite-On Technology Corporation, Guangzhou, China, (5) School of Electronic Science and Engineering, Nanjing University, China)
mathjax: true
---

* content
{:toc}

##### Abstract
With the ever-growing storage density, high-speed, and low-cost data access, flash memory has inevitably become popular. Multi-level cell (MLC) NAND flash memory, which can well balance the data density and memory stability, has occupied the largest market share of flash memory. With the aggressive memory scaling, however, the reliability decays sharply owing to multiple interferences. Therefore, the control system should be embedded with a suitable error correction code (ECC) to guarantee the data integrity and accuracy. We proposed the pre-check scheme which is a multi-strategy polar code scheme to strike a balance between reasonable frame error rate (FER) and decoding latency. Three decoders namely binary-input, quantized-soft, and pure-soft decoders are embedded in this scheme. Since the calculation of soft log-likelihood ratio (LLR) inputs needs multiple sensing operations and optional quantization boundaries, a 2-bit quantized hard-decision decoder is proposed to outperform the hard-decoded LDPC bit-flipping decoder with fewer sensing operations. We notice that polar codes have much lower computational complexity compared to LDPC codes. The stepwise maximum mutual information (SMMI) scheme is also proposed to obtain overlapped boundaries without exhausting search. The mapping scheme using Gray code is employed and proved to achieve better raw error performance compared to other alternatives. Hardware architectures are also given in this paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.04576](https://arxiv.org/abs/1802.04576)

##### PDF
[https://arxiv.org/pdf/1802.04576](https://arxiv.org/pdf/1802.04576)

