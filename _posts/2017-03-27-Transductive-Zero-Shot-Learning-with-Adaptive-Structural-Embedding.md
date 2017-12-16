---
layout: post
title: "Transductive Zero-Shot Learning with Adaptive Structural Embedding"
date: 2017-03-27 01:44:41
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding Classification Prediction
author: Yunlong Yu, Zhong Ji, Jichang Guo, Yanwei Pang
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) endows the computer vision system with the inferential capability to recognize instances of a new category that has never seen before. Two fundamental challenges in it are visual-semantic embedding and domain adaptation in cross-modality learning and unseen class prediction steps, respectively. To address both challenges, this paper presents two corresponding methods named Adaptive STructural Embedding (ASTE) and Self-PAsed Selective Strategy (SPASS), respectively. Specifically, ASTE formulates the visualsemantic interactions in a latent structural SVM framework to adaptively adjust the slack variables to embody the different reliableness among training instances. In this way, the reliable instances are imposed with small punishments, wheras the less reliable instances are imposed with more severe punishments. Thus, it ensures a more discriminative embedding. On the other hand, SPASS offers a framework to alleviate the domain shift problem in ZSL, which exploits the unseen data in an easy to hard fashion. Particularly, SPASS borrows the idea from selfpaced learning by iteratively selecting the unseen instances from reliable to less reliable to gradually adapt the knowledge from the seen domain to the unseen domain. Subsequently, by combining SPASS and ASTE, we present a self-paced Transductive ASTE (TASTE) method to progressively reinforce the classification capacity. Extensive experiments on three benchmark datasets (i.e., AwA, CUB, and aPY) demonstrate the superiorities of ASTE and TASTE. Furthermore, we also propose a fast training (FT) strategy to improve the efficiency of most of existing ZSL methods. The FT strategy is surprisingly simple and general enough, which can speed up the training time of most existing methods by 4~300 times while holding the previous performance.

##### Abstract (translated by Google)
零点学习（ZSL）赋予计算机视觉系统以推理能力，以识别以前从未见过的新类别的实例。其中两个基本挑战是视觉语义嵌入和领域适应在跨模态学习和看不见的类预测步骤，分别。为了解决这两个挑战，本文分别介绍了两种相应的方法：自适应结构嵌入（ASTE）和自适应选择策略（SPASS）。具体而言，ASTE在潜在的结构SVM框架中形成视觉语义交互，自适应地调整松弛变量以体现不同训练实例之间的可靠性。这样，可靠的例子就会受到很小的惩罚，而惩罚越不可靠的惩罚越严厉。因此，它确保了更有区别的嵌入。另一方面，SPASS提供了一个框架来缓解ZSL中的域转换问题，这种转换问题以难以理解的方式利用不可见的数据。特别是，SPASS借鉴了自适应学习的思想，通过反复选择从可靠到不可靠的不可见实例，逐步将知识从所看到的领域适应到不可见的领域。随后，通过结合SPASS和ASTE，我们提出了一种自我调节的转导ASTE（TASTE）方法来逐步加强分类能力。对三个基准数据集（即AwA，CUB和aPY）的大量实验证明了ASTE和TASTE的优越性。此外，我们还提出了快速培训（FT）战略，以提高现有的大多数ZSL方法的效率。英国“金融时报”的策略非常简单而通用，可以将现有的大多数方法的培训时间缩短4〜300倍，同时保持以往的表现。

##### URL
[https://arxiv.org/abs/1703.08897](https://arxiv.org/abs/1703.08897)

##### PDF
[https://arxiv.org/pdf/1703.08897](https://arxiv.org/pdf/1703.08897)

