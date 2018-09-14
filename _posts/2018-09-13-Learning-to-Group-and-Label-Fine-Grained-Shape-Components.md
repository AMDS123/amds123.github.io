---
layout: post
title: "Learning to Group and Label Fine-Grained Shape Components"
date: 2018-09-13 16:31:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Xiaogang Wang, Bin Zhou, Haiyue Fang, Xiaowu Chen, Qinping Zhao, Kai Xu
mathjax: true
---

* content
{:toc}

##### Abstract
A majority of stock 3D models in modern shape repositories are assembled with many fine-grained components. The main cause of such data form is the component-wise modeling process widely practiced by human modelers. These modeling components thus inherently reflect some function-based shape decomposition the artist had in mind during modeling. On the other hand, modeling components represent an over-segmentation since a functional part is usually modeled as a multi-component assembly. Based on these observations, we advocate that labeled segmentation of stock 3D models should not overlook the modeling components and propose a learning solution to grouping and labeling of the fine-grained components. However, directly characterizing the shape of individual components for the purpose of labeling is unreliable, since they can be arbitrarily tiny and semantically meaningless. We propose to generate part hypotheses from the components based on a hierarchical grouping strategy, and perform labeling on those part groups instead of directly on the components. Part hypotheses are mid-level elements which are more probable to carry semantic information. A multiscale 3D convolutional neural network is trained to extract context-aware features for the hypotheses. To accomplish a labeled segmentation of the whole shape, we formulate higher-order conditional random fields (CRFs) to infer an optimal label assignment for all components. Extensive experiments demonstrate that our method achieves significantly robust labeling results on raw 3D models from public shape repositories. Our work also contributes the first benchmark for component-wise labeling.

##### Abstract (translated by Google)
现代形状存储库中的大多数3D模型都与许多细粒度组件组装在一起。这种数据形式的主要原因是人类建模者广泛实施的组件建模过程。因此，这些建模组件固有地反映了艺术家在建模过程中想到的一些基于功能的形状分解。另一方面，建模组件表示过度分割，因为功能部件通常被建模为多组件组件。基于这些观察，我们提倡对库存3D模型进行标记分割不应忽略建模组件，并提出一种学习解决方案来对细粒度组件进行分组和标记。然而，为了标记而直接表征各个组件的形状是不可靠的，因为它们可以是任意微小的并且在语义上没有意义。我们建议基于分层分组策略从组件生成部分假设，并对这些部分组执行标记，而不是直接在组件上执行标记。部分假设是更有可能携带语义信息的中级元素。训练多尺度3D卷积神经网络以提取假设的上下文感知特征。为了完成整个形状的标记分割，我们制定高阶条件随机场（CRF）以推断所有组件的最佳标签分配。大量实验表明，我们的方法在公共形状存储库的原始3D模型上实现了非常强大的标记结果。我们的工作也为组件标签提供了第一个基准。

##### URL
[http://arxiv.org/abs/1809.05050](http://arxiv.org/abs/1809.05050)

##### PDF
[http://arxiv.org/pdf/1809.05050](http://arxiv.org/pdf/1809.05050)

