---
layout: post
title: "Escoin: Efficient Sparse Convolutional Neural Network Inference on GPUs"
date: 2019-04-03 21:11:27
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization Inference
author: Xuhao Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved remarkable accuracy in many artificial intelligence applications, e.g. computer vision, at the cost of a large number of parameters and high computational complexity. Weight pruning can compress DNN models by removing redundant parameters in the networks, but it brings sparsity in the weight matrix, and therefore makes the computation inefficient on GPUs. Although pruning can remove more than 80% of the weights, it actually hurts inference performance (speed) when running models on GPUs. 
 Two major problems cause this unsatisfactory performance on GPUs. First, lowering convolution onto matrix multiplication reduces data reuse opportunities and wastes memory bandwidth. Second, the sparsity brought by pruning makes the computation irregular, which leads to inefficiency when running on massively parallel GPUs. To overcome these two limitations, we propose Escort, an efficient sparse convolutional neural networks on GPUs. Instead of using the lowering method, we choose to compute the sparse convolutions directly. We then orchestrate the parallelism and locality for the direct sparse convolution kernel, and apply customized optimization techniques to further improve performance. Evaluation on NVIDIA GPUs show that Escort can improve sparse convolution speed by 2.63x and 3.07x, and inference speed by 1.43x and 1.69x, compared to CUBLAS and CUSPARSE respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.10280](http://arxiv.org/abs/1802.10280)

##### PDF
[http://arxiv.org/pdf/1802.10280](http://arxiv.org/pdf/1802.10280)

