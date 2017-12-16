---
layout: post
title: "Real Time Fine-Grained Categorization with Accuracy and Interpretability"
date: 2016-10-04 02:20:18
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Shaoli Huang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
A well-designed fine-grained categorization system usually has three contradictory requirements: accuracy (the ability to identify objects among subordinate categories); interpretability (the ability to provide human-understandable explanation of recognition system behavior); and efficiency (the speed of the system). To handle the trade-off between accuracy and interpretability, we propose a novel "Deeper Part-Stacked CNN" architecture armed with interpretability by modeling subtle differences between object parts. The proposed architecture consists of a part localization network, a two-stream classification network that simultaneously encodes object-level and part-level cues, and a feature vectors fusion component. Specifically, the part localization network is implemented by exploring a new paradigm for key point localization that first samples a small number of representable pixels and then determine their labels via a convolutional layer followed by a softmax layer. We also use a cropping layer to extract part features and propose a scale mean-max layer for feature fusion learning. Experimentally, our proposed method outperform state-of-the-art approaches both in part localization task and classification task on Caltech-UCSD Birds-200-2011. Moreover, by adopting a set of sharing strategies between the computation of multiple object parts, our single model is fairly efficient running at 32 frames/sec.

##### Abstract (translated by Google)
精心设计的细粒度分类系统通常有三个相互矛盾的要求：准确性（在下属类别中识别对象的能力）;可解释性（提供人类可理解的识别系统行为解释的能力）;和效率（系统的速度）。为了处理准确性和可解释性之间的平衡，我们提出了一种新颖的“更深的部分堆叠的CNN”架构，通过对对象部分之间的细微差异进行建模来提供可解释性。所提出的体系结构由部分定位网络，同时编码对象级和部分级提示的双流分类网络以及特征向量融合部分组成。具体来说，部分定位网络是通过探索关键点定位的新范例来实现的，首先对少量可表示的像素进行采样，然后通过卷积层，然后用softmax层来确定它们的标签。我们还使用裁剪图层来提取部分特征，并提出了一个尺度平均最大值层来进行特征融合学习。在实验上，我们提出的方法在加州理工学院的UCSD Birds-200-2011部分定位任务和分类任务方面均优于最新的方法。而且，通过在多个对象部分的计算之间采用一组共享策略，我们的单个模型在32帧/秒的情况下相当高效。

##### URL
[https://arxiv.org/abs/1610.00824](https://arxiv.org/abs/1610.00824)

##### PDF
[https://arxiv.org/pdf/1610.00824](https://arxiv.org/pdf/1610.00824)

