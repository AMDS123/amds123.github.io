---
layout: post
title: "Hybrid Binary Networks: Optimizing for Accuracy, Efficiency and Memory"
date: 2018-04-11 08:27:49
categories: arXiv_CV
tags: arXiv_CV
author: Ameya Prabhu, Vishal Batchu, Rohit Gajawada, Sri Aurobindo Munagala, Anoop Namboodiri
mathjax: true
---

* content
{:toc}

##### Abstract
Binarization is an extreme network compression approach that provides large computational speedups along with energy and memory savings, albeit at significant accuracy costs. We investigate the question of where to binarize inputs at layer-level granularity and show that selectively binarizing the inputs to specific layers in the network could lead to significant improvements in accuracy while preserving most of the advantages of binarization. We analyze the binarization tradeoff using a metric that jointly models the input binarization-error and computational cost and introduce an efficient algorithm to select layers whose inputs are to be binarized. Practical guidelines based on insights obtained from applying the algorithm to a variety of models are discussed. Experiments on Imagenet dataset using AlexNet and ResNet-18 models show 3-4% improvements in accuracy over fully binarized networks with minimal impact on compression and computational speed. The improvements are even more substantial on sketch datasets like TU-Berlin, where we match state-of-the-art accuracy as well, getting over 8% increase in accuracies. We further show that our approach can be applied in tandem with other forms of compression that deal with individual layers or overall model compression (e.g., SqueezeNets). Unlike previous quantization approaches, we are able to binarize the weights in the last layers of a network, which often have a large number of parameters, resulting in significant improvement in accuracy over fully binarized models.

##### Abstract (translated by Google)
二进制化是一种极端的网络压缩方法，它提供了大量的计算加速以及节省的能量和内存，尽管其成本很高。我们调查了在层级粒度将输入二值化的问题，并且表明有选择地将输入二进制化为网络中特定层的输入可以导致准确性的显着提高，同时保留二值化的大部分优点。我们使用一个度量来分析二值化折衷，该度量将输入二值化误差和计算成本联合建模，并引入一种有效的算法来选择其输入将被二进制化的层。讨论了基于将该算法应用于各种模型所获得的见解的实用准则。使用AlexNet和ResNet-18模型对Imagenet数据集进行的实验显示，与完全二值化网络相比，精度提高3-4％，而对压缩和计算速度的影响最小。在像TU-Berlin这样的草图数据集中，我们的改进更加充实，我们也可以匹配最新的精度，准确度提高8％以上。我们进一步表明，我们的方法可以与处理单个图层或整体模型压缩的其他形式的压缩（例如SqueezeNets）一起使用。与以前的量化方法不同，我们能够对网络最后一层的权重进行二值化处理，这些网络通常具有大量参数，与完全二值化模型相比，可以显着提高精度。

##### URL
[https://arxiv.org/abs/1804.03867](https://arxiv.org/abs/1804.03867)

##### PDF
[https://arxiv.org/pdf/1804.03867](https://arxiv.org/pdf/1804.03867)

