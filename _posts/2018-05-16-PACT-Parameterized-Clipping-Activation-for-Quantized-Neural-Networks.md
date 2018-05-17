---
layout: post
title: "PACT: Parameterized Clipping Activation for Quantized Neural Networks"
date: 2018-05-16 01:19:43
categories: arXiv_AI
tags: arXiv_AI Classification Deep_Learning
author: Jungwook Choi, Zhuo Wang, Swagath Venkataramani, Pierce I-Jen Chuang, Vijayalakshmi Srinivasan, Kailash Gopalakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning algorithms achieve high classification accuracy at the expense of significant computation cost. To address this cost, a number of quantization schemes have been proposed - but most of these techniques focused on quantizing weights, which are relatively smaller in size compared to activations. This paper proposes a novel quantization scheme for activations during training - that enables neural networks to work well with ultra low precision weights and activations without any significant accuracy degradation. This technique, PArameterized Clipping acTivation (PACT), uses an activation clipping parameter $\alpha$ that is optimized during training to find the right quantization scale. PACT allows quantizing activations to arbitrary bit precisions, while achieving much better accuracy relative to published state-of-the-art quantization schemes. We show, for the first time, that both weights and activations can be quantized to 4-bits of precision while still achieving accuracy comparable to full precision networks across a range of popular models and datasets. We also show that exploiting these reduced-precision computational units in hardware can enable a super-linear improvement in inferencing performance due to a significant reduction in the area of accelerator compute engines coupled with the ability to retain the quantized model and activation data in on-chip memories.

##### Abstract (translated by Google)
深度学习算法以高计算成本为代价实现了高分类精度。为了解决这个成本问题，已经提出了一些量化方案 - 但是这些技术大多集中在量化权重上，权重相对于激活而言相对较小。本文提出了一种用于训练期间激活的新型量化方案 - 使神经网络能够以超低精度加权和激活良好地工作，而不会显着降低精度。这种技术，参数化裁剪活动（PACT），使用在训练期间优化的激活限幅参数$ \ alpha $来找到正确的量化比例。 PACT允许将激活量化为任意比特精度，同时相对于公布的最新量化方案实现更好的准确性。我们首次表明，权重和激活可以被量化到4位的精度，同时仍然可以在一系列流行的模型和数据集中实现与全精度网络相当的精度。我们还表明，在硬件中利用这些精度降低的计算单元可以实现推理性能的超线性改进，这是因为加速计算引擎的面积显着减小，并且能够将量化模型和激活数据保留在片上系统中，芯片存储器。

##### URL
[http://arxiv.org/abs/1805.06085](http://arxiv.org/abs/1805.06085)

##### PDF
[http://arxiv.org/pdf/1805.06085](http://arxiv.org/pdf/1805.06085)

