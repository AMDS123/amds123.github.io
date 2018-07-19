---
layout: post
title: "Bridging the Accuracy Gap for 2-bit Quantized Neural Networks"
date: 2018-07-17 13:36:57
categories: arXiv_CV
tags: arXiv_CV Attention Classification Deep_Learning
author: Jungwook Choi, Pierce I-Jen Chuang, Zhuo Wang, Swagath Venkataramani, Vijayalakshmi Srinivasan, Kailash Gopalakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning algorithms achieve high classification accuracy at the expense of significant computation cost. In order to reduce this cost, several quantization schemes have gained attention recently with some focusing on weight quantization, and others focusing on quantizing activations. This paper proposes novel techniques that target weight and activation quantizations separately resulting in an overall quantized neural network (QNN). The activation quantization technique, PArameterized Clipping acTivation (PACT), uses an activation clipping parameter $\alpha$ that is optimized during training to find the right quantization scale. The weight quantization scheme, statistics-aware weight binning (SAWB), finds the optimal scaling factor that minimizes the quantization error based on the statistical characteristics of the distribution of weights without the need for an exhaustive search. The combination of PACT and SAWB results in a 2-bit QNN that achieves state-of-the-art classification accuracy (comparable to full precision networks) across a range of popular models and datasets.

##### Abstract (translated by Google)
深度学习算法以显着的计算成本为代价实现高分类精度。为了降低这种成本，最近几种量化方案受到关注，一些侧重于权重量化，另一些侧重于量化激活。本文提出了分别针对权重和激活量化的新技术，从而产生了整体量化神经网络（QNN）。激活量化技术，PArameterized Clipping acTivation（PACT），使用在训练期间优化的激活限幅参数$ \ alpha $来找到正确的量化比例。权重量化方案，统计感知权重合并（SAWB），基于权重分布的统计特性找到最小化量化误差的最佳缩放因子，而不需要穷举搜索。 PACT和SAWB的组合产生2位QNN，在一系列流行的模型和数据集中实现了最先进的分类精度（与全精度网络相当）。

##### URL
[https://arxiv.org/abs/1807.06964](https://arxiv.org/abs/1807.06964)

##### PDF
[https://arxiv.org/pdf/1807.06964](https://arxiv.org/pdf/1807.06964)

