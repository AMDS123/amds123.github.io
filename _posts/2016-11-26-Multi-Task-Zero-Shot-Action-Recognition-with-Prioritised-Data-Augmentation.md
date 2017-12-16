---
layout: post
title: "Multi-Task Zero-Shot Action Recognition with Prioritised Data Augmentation"
date: 2016-11-26 05:51:11
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Embedding Inference Recognition
author: Xun Xu, Timothy M. Hospedales, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Learning (ZSL) promises to scale visual recognition by bypassing the conventional model training requirement of annotated examples for every category. This is achieved by establishing a mapping connecting low-level features and a semantic description of the label space, referred as visual-semantic mapping, on auxiliary data. Reusing the learned mapping to project target videos into an embedding space thus allows novel-classes to be recognised by nearest neighbour inference. However, existing ZSL methods suffer from auxiliary-target domain shift intrinsically induced by assuming the same mapping for the disjoint auxiliary and target classes. This compromises the generalisation accuracy of ZSL recognition on the target data. In this work, we improve the ability of ZSL to generalise across this domain shift in both model- and data-centric ways by formulating a visual-semantic mapping with better generalisation properties and a dynamic data re-weighting method to prioritise auxiliary data that are relevant to the target classes. Specifically: (1) We introduce a multi-task visual-semantic mapping to improve generalisation by constraining the semantic mapping parameters to lie on a low-dimensional manifold, (2) We explore prioritised data augmentation by expanding the pool of auxiliary data with additional instances weighted by relevance to the target domain. The proposed new model is applied to the challenging zero-shot action recognition problem to demonstrate its advantages over existing ZSL models.

##### Abstract (translated by Google)
零点射击学习（ZSL）有望通过绕过每个类别的注释示例的传统模型训练要求来缩放视觉识别。这是通过在辅助数据上建立连接低级特征和标签空间的语义描述（称为视觉语义映射）的映射来实现的。重新使用所学习的映射将目标视频投影到嵌入空间中，从而允许新近类别被最近邻居推断所识别。然而，现有的ZSL方法通过假设不相交的辅助类和目标类的相同映射而本质上受到辅助 - 目标域移位的困扰。这降低了目标数据上ZSL识别的泛化精度。在这项工作中，我们通过制定具有更好泛化特性的可视化语义映射和动态数据重新加权方法来优化辅助数据，从而提高了ZSL在以模型和数据为中心的方式中跨越这一领域转变与目标类相关。具体来说：（1）引入多任务视觉语义映射，通过将语义映射参数约束在一个低维流形上来提高泛化能力;（2）通过扩充辅助数据池通过与目标域的相关性加权的实例。所提出的新模型被应用于具有挑战性的零点动作识别问题，以证明其优于现有ZSL模型的优点。

##### URL
[https://arxiv.org/abs/1611.08663](https://arxiv.org/abs/1611.08663)

##### PDF
[https://arxiv.org/pdf/1611.08663](https://arxiv.org/pdf/1611.08663)

