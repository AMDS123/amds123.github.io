---
layout: post
title: "Tinkering Under the Hood: Interactive Zero-Shot Learning with Net Surgery"
date: 2016-12-15 01:27:10
categories: arXiv_CV
tags: arXiv_CV Knowledge Weakly_Supervised Classification Relation
author: Vivek Krishnan, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of visual net surgery, in which a CNN can be reconfigured without extra data to recognize novel concepts that may be omitted from the training set. While most prior work make use of linguistic cues for such "zero-shot" learning, we do so by using a pictorial language representation of the training set, implicitly learned by a CNN, to generalize to new classes. To this end, we introduce a set of visualization techniques that better reveal the activation patterns and relations between groups of CNN filters. We next demonstrate that knowledge of pictorial languages can be used to rewire certain CNN neurons into a part model, which we call a pictorial language classifier. We demonstrate the robustness of simple PLCs by applying them in a weakly supervised manner: labeling unlabeled concepts for visual classes present in the training data. Specifically we show that a PLC built on top of a CNN trained for ImageNet classification can localize humans in Graz-02 and determine the pose of birds in PASCAL-VOC without extra labeled data or additional training. We then apply PLCs in an interactive zero-shot manner, demonstrating that pictorial languages are expressive enough to detect a set of visual classes in MS-COCO that never appear in the ImageNet training set.

##### Abstract (translated by Google)
我们考虑的是视网膜手术的任务，其中CNN可以在没有额外数据的情况下重新配置，以识别可能从训练集中省略的新概念。虽然大多数先前的工作利用语言学的线索来进行这种“零点”学习，但是我们通过使用由CNN隐式学习的训练集的图像语言表示来推广到新的类别。为此，我们引入了一组可视化技术，更好地揭示CNN滤波器组之间的激活模式和关系。我们接下来证明了图形语言的知识可以用来把某些CNN神经元重新连接成一个部分模型，我们称之为图像语言分类器。我们通过以弱监督的方式应用简单的PLC来证明其稳健性：为训练数据中存在的视觉类别标记未标记的概念。具体而言，我们展示了一个建立在CNN培训的ImageNet分类之上的PLC可以定位Graz-02中的人类并确定PASCAL-VOC中鸟类的姿势，而无需额外的标记数据或额外的培训。然后，我们以交互零点方式应用PLC，证明图形语言具有足够的表现力来检测MS-COCO中从未出现在ImageNet训练集中的一组视觉类。

##### URL
[https://arxiv.org/abs/1612.04901](https://arxiv.org/abs/1612.04901)

##### PDF
[https://arxiv.org/pdf/1612.04901](https://arxiv.org/pdf/1612.04901)

