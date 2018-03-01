---
layout: post
title: "Escort: Efficient Sparse Convolutional Neural Networks on GPUs"
date: 2018-02-28 06:31:45
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization Inference
author: Xuhao Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved remarkable accuracy in many artificial intelligence applications, e.g. computer vision, at the cost of a large number of parameters and high computational complexity. Weight pruning can compress DNN models by removing redundant parameters in the networks, but it brings sparsity in the weight matrix, and therefore makes the computation inefficient on GPUs. Although pruning can remove more than 80% of the weights, it actually hurts inference performance (speed) when running models on GPUs. 
 Two major problems cause this unsatisfactory performance on GPUs. First, lowering convolution onto matrix multiplication reduces data reuse opportunities and wastes memory bandwidth. Second, the sparsity brought by pruning makes the computation irregular, which leads to inefficiency when running on massively parallel GPUs. To overcome these two limitations, we propose Escort, an efficient sparse convolutional neural networks on GPUs. Instead of using the lowering method, we choose to compute the sparse convolutions directly. We then orchestrate the parallelism and locality for the direct sparse convolution kernel, and apply customized optimization techniques to further improve performance. Evaluation on NVIDIA GPUs show that Escort can improve sparse convolution speed by 2.63x and 3.07x, and inference speed by 1.38x and 1.60x, compared to CUBLAS and CUSPARSE respectively.

##### Abstract (translated by Google)
深度神经网络在许多人工智能应用中取得了显着的精度，例如，计算机视觉，代价是大量参数和高计算复杂性。加权修剪可以通过去除网络中的冗余参数来压缩DNN模型，但是它会在权重矩阵中带来稀疏性，并因此导致GPU上的计算效率低下。虽然修剪可以消除超过80％的权重，但在GPU上运行模型时，它实际上会损害推理性能（速度）。
 两个主要问题导致GPU不能令人满意的性能。首先，将卷积降至矩阵乘法减少了数据重用机会并浪费了内存带宽。其次，修剪带来的稀疏使得计算不规则，导致在大规模并行GPU上运行时效率低下。为了克服这两个限制，我们在GPU上提出了Escort，一种高效的稀疏卷积神经网络。我们不用降低方法，而是直接计算稀疏卷积。然后，我们为直接稀疏卷积核心编排并行性和局部性，并应用定制优化技术来进一步提高性能。对NVIDIA GPU的评估表明，与CUBLAS和CUSPARSE相比，Escort可以将稀疏卷积速度提高2.63倍和3.07倍，推理速度分别提高1.38倍和1.60倍。

##### URL
[http://arxiv.org/abs/1802.10280](http://arxiv.org/abs/1802.10280)

##### PDF
[http://arxiv.org/pdf/1802.10280](http://arxiv.org/pdf/1802.10280)

