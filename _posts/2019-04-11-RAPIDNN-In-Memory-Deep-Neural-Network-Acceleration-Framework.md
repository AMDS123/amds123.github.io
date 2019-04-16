---
layout: post
title: "RAPIDNN: In-Memory Deep Neural Network Acceleration Framework"
date: 2019-04-11 18:36:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Speech_Recognition Recognition
author: Mohsen Imani, Mohammad Samragh, Yeseong Kim, Saransh Gupta, Farinaz Koushanfar, Tajana Rosing
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) have demonstrated effectiveness for various applications such as image processing, video segmentation, and speech recognition. Running state-of-the-art DNNs on current systems mostly relies on either generalpurpose processors, ASIC designs, or FPGA accelerators, all of which suffer from data movements due to the limited onchip memory and data transfer bandwidth. In this work, we propose a novel framework, called RAPIDNN, which processes all DNN operations within the memory to minimize the cost of data movement. To enable in-memory processing, RAPIDNN reinterprets a DNN model and maps it into a specialized accelerator, which is designed using non-volatile memory blocks that model four fundamental DNN operations, i.e., multiplication, addition, activation functions, and pooling. The framework extracts representative operands of a DNN model, e.g., weights and input values, using clustering methods to optimize the model for in-memory processing. Then, it maps the extracted operands and their precomputed results into the accelerator memory blocks. At runtime, the accelerator identifies computation results based on efficient in-memory search capability which also provides tunability of approximation to further improve computation efficiency. Our evaluation shows that RAPIDNN achieves 68.4x, 49.5x energy efficiency improvement and 48.1x, 10.9x speedup as compared to ISAAC and PipeLayer, the state-of-the-art DNN accelerators, while ensuring less than 0.3% of quality loss.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.05794](https://arxiv.org/abs/1806.05794)

##### PDF
[https://arxiv.org/pdf/1806.05794](https://arxiv.org/pdf/1806.05794)

