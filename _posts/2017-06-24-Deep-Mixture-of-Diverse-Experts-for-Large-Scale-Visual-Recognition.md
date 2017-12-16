---
layout: post
title: "Deep Mixture of Diverse Experts for Large-Scale Visual Recognition"
date: 2017-06-24 03:41:37
categories: arXiv_CV
tags: arXiv_CV Ontology CNN Recognition
author: Tianyi Zhao, Jun Yu, Zhenzhong Kuang, Wei Zhang, Jianping Fan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a deep mixture of diverse experts algorithm is developed for seamlessly combining a set of base deep CNNs (convolutional neural networks) with diverse outputs (task spaces), e.g., such base deep CNNs are trained to recognize different subsets of tens of thousands of atomic object classes. First, a two-layer (category layer and object class layer) ontology is constructed to achieve more effective solution for task group generation, e.g., assigning the semantically-related atomic object classes at the sibling leaf nodes into the same task group because they may share similar learning complexities. Second, one particular base deep CNNs with $M+1$ ($M \leq 1,000$) outputs is learned for each task group to recognize its $M$ atomic object classes effectively and identify one special class of "not-in-group" automatically, and the network structure (numbers of layers and units in each layer) of the well-designed AlexNet is directly used to configure such base deep CNNs. A deep multi-task learning algorithm is developed to leverage the inter-class visual similarities to learn more discriminative base deep CNNs and multi-task softmax for enhancing the separability of the atomic object classes in the same task group. Finally, all these base deep CNNs with diverse outputs (task spaces) are seamlessly combined to form a deep mixture of diverse experts for recognizing tens of thousands of atomic object classes. Our experimental results have demonstrated that our deep mixture of diverse experts algorithm can achieve very competitive results on large-scale visual recognition.

##### Abstract (translated by Google)
在本文中，为了将一组基础深度的CNN（卷积神经网络）与不同的输出（任务空间）无缝地组合起来，开发了多种专家的深层混合算法，例如，这样的基础深度CNN被训练识别数十个数以千计的原子对象类。首先，构造两层（类别层和对象类层）本体，以实现更有效的任务组生成，例如将同级叶节点上的语义相关的原子对象类分配到同一个任务组中，因为它们可能分享类似的学习复杂性。其次，为每个任务组学习一个具有$ M + 1 $（$ M \ leq 1000 $）输出的基础深度CNN，以有效地识别其$ M $原子对象类，并识别一个特殊的“不在组“，精心设计的AlexNet的网络结构（每层中的层数和单元数量）直接用于配置这样的基础深度CNN。开发了一个深度的多任务学习算法，以利用类间视觉相似性来学习更多的区分性底层深度CNN和多任务softmax，以增强同一任务组中的原子对象类的可分离性。最后，所有这些具有不同输出（任务空间）的基础深度CNN被无缝地结合起来，形成了一个由多种专家组成的深度混合体，以识别数以万计的原子对象类。我们的实验结果表明，我们深入的多种专家算法的混合可以在大规模的视觉识别上取得非常有竞争力的结果。

##### URL
[https://arxiv.org/abs/1706.07901](https://arxiv.org/abs/1706.07901)

##### PDF
[https://arxiv.org/pdf/1706.07901](https://arxiv.org/pdf/1706.07901)

