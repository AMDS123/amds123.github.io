---
layout: post
title: "BAM: Bottleneck Attention Module"
date: 2018-07-17 15:55:31
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Detection
author: Jongchan Park, Sanghyun Woo, Joon-Young Lee, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep neural networks have been developed via architecture search for stronger representational power. In this work, we focus on the effect of attention in general deep neural networks. We propose a simple and effective attention module, named Bottleneck Attention Module (BAM), that can be integrated with any feed-forward convolutional neural networks. Our module infers an attention map along two separate pathways, channel and spatial. We place our module at each bottleneck of models where the downsampling of feature maps occurs. Our module constructs a hierarchical attention at bottlenecks with a number of parameters and it is trainable in an end-to-end manner jointly with any feed-forward models. We validate our BAM through extensive experiments on CIFAR-100, ImageNet-1K, VOC 2007 and MS COCO benchmarks. Our experiments show consistent improvement in classification and detection performances with various models, demonstrating the wide applicability of BAM. The code and models will be publicly available.

##### Abstract (translated by Google)
深度神经网络的最新进展已经通过架构搜索开发出更强的代表能力。在这项工作中，我们关注一般深度神经网络中注意力的影响。我们提出了一个简单有效的注意模块，名为瓶颈注意模块（BAM），可以与任何前馈卷积神经网络集成。我们的模块沿着两个独立的路径，即通道和空间推断出注意力图。我们将模块放置在模型的每个瓶颈中，其中发生特征映射的下采样。我们的模块通过许多参数在瓶颈上构建层次关注，并且可以与任何前馈模型一起以端到端的方式进行训练。我们通过CIFAR-100，ImageNet-1K，VOC 2007和MS COCO基准测试的大量实验来验证我们的BAM。我们的实验表明，各种模型在分类和检测性能方面都有一定的改进，证明了BAM的广泛适用性。代码和模型将公开提供。

##### URL
[http://arxiv.org/abs/1807.06514](http://arxiv.org/abs/1807.06514)

##### PDF
[http://arxiv.org/pdf/1807.06514](http://arxiv.org/pdf/1807.06514)

