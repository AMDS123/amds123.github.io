---
layout: post
title: "Visual Tracking via Shallow and Deep Collaborative Model"
date: 2016-07-27 11:18:12
categories: arXiv_CV
tags: arXiv_CV Tracking Classification Deep_Learning Quantitative
author: Bohan Zhuang, Lijun Wang, Huchuan Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a robust tracking method based on the collaboration of a generative model and a discriminative classifier, where features are learned by shallow and deep architectures, respectively. For the generative model, we introduce a block-based incremental learning scheme, in which a local binary mask is constructed to deal with occlusion. The similarity degrees between the local patches and their corresponding subspace are integrated to formulate a more accurate global appearance model. In the discriminative model, we exploit the advances of deep learning architectures to learn generic features which are robust to both background clutters and foreground appearance variations. To this end, we first construct a discriminative training set from auxiliary video sequences. A deep classification neural network is then trained offline on this training set. Through online fine-tuning, both the hierarchical feature extractor and the classifier can be adapted to the appearance change of the target for effective online tracking. The collaboration of these two models achieves a good balance in handling occlusion and target appearance change, which are two contradictory challenging factors in visual tracking. Both quantitative and qualitative evaluations against several state-of-the-art algorithms on challenging image sequences demonstrate the accuracy and the robustness of the proposed tracker.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于生成模型和判别分类器协作的鲁棒跟踪方法，其中特征分别由浅层和深层架构学习。对于生成模型，我们引入了一个基于块的增量学习方案，其中构造了局部二进制掩码来处理遮挡。将局部斑块与其对应的子空间的相似度综合起来，形成更准确的全局外观模型。在判别模型中，我们利用深度学习架构的进步来学习对背景杂乱和前景外观变化都强大的泛型特征。为此，我们首先从辅助视频序列中构造一个判别式训练集。然后在该训练集上离线训练深度分类神经网络。通过在线微调，层次特征提取器和分类器都可以适应目标的外观变化，进行有效的在线跟踪。这两种模型的协作在遮挡和目标外观变化方面达到了很好的平衡，这是视觉追踪中两个相互矛盾的挑战性因素。针对具有挑战性的图像序列上的几种最先进的算法的定量和定性评估证明了所提出的跟踪器的准确性和稳健性。

##### URL
[https://arxiv.org/abs/1607.08040](https://arxiv.org/abs/1607.08040)

##### PDF
[https://arxiv.org/pdf/1607.08040](https://arxiv.org/pdf/1607.08040)

