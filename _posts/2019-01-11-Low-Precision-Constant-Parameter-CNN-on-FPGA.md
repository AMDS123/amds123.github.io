---
layout: post
title: "Low Precision Constant Parameter CNN on FPGA"
date: 2019-01-11 23:40:35
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Thiam Khean Hah, Yeong Tat Liew, Jason Ong
mathjax: true
---

* content
{:toc}

##### Abstract
We report FPGA implementation results of low precision CNN convolution layers optimized for sparse and constant parameters. We describe techniques that amortizes the cost of common factor multiplication and automatically leverage dense hand tuned LUT structures. We apply this method to corner case residual blocks of Resnet on a sparse Resnet50 model to assess achievable utilization and frequency and demonstrate an effective performance of 131 and 23 TOP/chip for the corner case blocks. The projected performance on a multichip persistent implementation of all Resnet50 convolution layers is 10k im/s/chip at batch size 2. This is 1.37x higher than V100 GPU upper bound at the same batch size after normalizing for sparsity.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04969](https://arxiv.org/abs/1901.04969)

##### PDF
[https://arxiv.org/pdf/1901.04969](https://arxiv.org/pdf/1901.04969)

