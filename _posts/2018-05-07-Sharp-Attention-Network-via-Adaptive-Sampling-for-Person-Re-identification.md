---
layout: post
title: "Sharp Attention Network via Adaptive Sampling for Person Re-identification"
date: 2018-05-07 03:54:40
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification CNN
author: Chen Shen, Guo-Jun Qi, Rongxin Jiang, Zhongming Jin, Hongwei Yong, Yaowu Chen, Xian-Sheng Hua
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present novel sharp attention networks by adaptively sampling feature maps from convolutional neural networks (CNNs) for person re-identification (re-ID) problem. Due to the introduction of sampling-based attention models, the proposed approach can adaptively generate sharper attention-aware feature masks. This greatly differs from the gating-based attention mechanism that relies soft gating functions to select the relevant features for person re-ID. In contrast, the proposed sampling-based attention mechanism allows us to effectively trim irrelevant features by enforcing the resultant feature masks to focus on the most discriminative features. It can produce sharper attentions that are more assertive in localizing subtle features relevant to re-identifying people across cameras. For this purpose, a differentiable Gumbel-Softmax sampler is employed to approximate the Bernoulli sampling to train the sharp attention networks. Extensive experimental evaluations demonstrate the superiority of this new sharp attention model for person re-ID over the other state-of-the-art methods on three challenging benchmarks including CUHK03, Market-1501, and DukeMTMC-reID.

##### Abstract (translated by Google)
在本文中，我们通过自适应采样来自卷积神经网络（CNN）的人重新识别（重新识别）问题的特征映射来呈现新颖的尖锐关注网络。由于引入了基于抽样的注意模型，所提出的方法可以自适应地生成更敏锐的注意力特征掩码。这与基于门控的注意机制有很大的不同，后者依赖于软门控功能来为人员重新选择相关功能。相反，所提出的基于抽样的关注机制使我们能够通过强化所产生的特征掩模来关注最具有区别性的特征来有效地修剪不相关的特征。它可以产生更强烈的注意力，这些注意力更加自信地定位与重新识别相机中的人物有关的细微特征。为此，采用可微分的Gumbel-Softmax采样器来逼近伯努利采样来训练尖锐的关注网络。广泛的实验评估证明了这个新的关于人员重新识别的尖锐关注模型在包括CUHK03，Market-1501和DukeMMC-reID在内的三个具有挑战性的基准测试中优于其他最先进方法的优势。

##### URL
[http://arxiv.org/abs/1805.02336](http://arxiv.org/abs/1805.02336)

##### PDF
[http://arxiv.org/pdf/1805.02336](http://arxiv.org/pdf/1805.02336)

