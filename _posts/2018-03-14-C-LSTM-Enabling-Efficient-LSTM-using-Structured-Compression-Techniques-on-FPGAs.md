---
layout: post
title: "C-LSTM: Enabling Efficient LSTM using Structured Compression Techniques on FPGAs"
date: 2018-03-14 04:19:37
categories: arXiv_CV
tags: arXiv_CV Sparse Inference RNN Recognition
author: Shuo Wang, Zhe Li, Caiwen Ding, Bo Yuan, Yanzhi Wang, Qinru Qiu, Yun Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, significant accuracy improvement has been achieved for acoustic recognition systems by increasing the model size of Long Short-Term Memory (LSTM) networks. Unfortunately, the ever-increasing size of LSTM model leads to inefficient designs on FPGAs due to the limited on-chip resources. The previous work proposes to use a pruning based compression technique to reduce the model size and thus speedups the inference on FPGAs. However, the random nature of the pruning technique transforms the dense matrices of the model to highly unstructured sparse ones, which leads to unbalanced computation and irregular memory accesses and thus hurts the overall performance and energy efficiency. In contrast, we propose to use a structured compression technique which could not only reduce the LSTM model size but also eliminate the irregularities of computation and memory accesses. This approach employs block-circulant instead of sparse matrices to compress weight matrices and reduces the storage requirement from $\mathcal{O}(k^2)$ to $\mathcal{O}(k)$. Fast Fourier Transform algorithm is utilized to further accelerate the inference by reducing the computational complexity from $\mathcal{O}(k^2)$ to $\mathcal{O}(k\text{log}k)$. The datapath and activation functions are quantized as 16-bit to improve the resource utilization. More importantly, we propose a comprehensive framework called C-LSTM to automatically optimize and implement a wide range of LSTM variants on FPGAs. According to the experimental results, C-LSTM achieves up to 18.8X and 33.5X gains for performance and energy efficiency compared with the state-of-the-art LSTM implementation under the same experimental setup, and the accuracy degradation is very small.

##### Abstract (translated by Google)
最近，通过增加长期短期记忆（LSTM）网络的模型尺寸，声学识别系统已经实现了显着的准确度提高。不幸的是，由于片上资源有限，LSTM模型的规模不断增大导致FPGA设计效率低下。以前的工作提出使用基于修剪的压缩技术来减小模型尺寸，从而加速FPGA的推断。然而，修剪技术的随机特性将模型的稠密矩阵转换为高度非结构化的稀疏矩阵，这导致不平衡的计算和不规则的存储器访问，并因此伤害整体性能和能量效率。相比之下，我们建议使用结构化压缩技术，该技术不仅可以减少LSTM模型大小，还可以消除计算和内存访问的不规则性。该方法采用块循环而不是稀疏矩阵来压缩加权矩阵，并将存储需求从$ \ mathcal {O}（k ^ 2）$减少到$ \ mathcal {O}（k）$。利用快速傅里叶变换算法，通过将计算复杂度从$ \ mathcal {O}（k ^ 2）$减少到$ \ mathcal {O}（k \ text {log} k）$来进一步加速推理。数据路径和激活函数被量化为16位以提高资源利用率。更重要的是，我们提出了一个名为C-LSTM的综合框架，用于在FPGA上自动优化和实施各种LSTM变体。根据实验结果，C-LSTM在同样的实验设置下，与最先进的LSTM实现相比，在性能和能量效率方面实现了高达18.8倍和33.5倍的增益，并且精度降低非常小。

##### URL
[https://arxiv.org/abs/1803.06305](https://arxiv.org/abs/1803.06305)

##### PDF
[https://arxiv.org/pdf/1803.06305](https://arxiv.org/pdf/1803.06305)

