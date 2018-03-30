---
layout: post
title: "DeepVoting: A Robust and Explainable Deep Network for Semantic Part Detection under Partial Occlusion"
date: 2018-03-29 17:56:07
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Detection Relation
author: Zhishuai Zhang, Cihang Xie, Jianyu Wang, Lingxi Xie, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the task of detecting semantic parts of an object, e.g., a wheel of a car, under partial occlusion. We propose that all models should be trained without seeing occlusions while being able to transfer the learned knowledge to deal with occlusions. This setting alleviates the difficulty in collecting an exponentially large dataset to cover occlusion patterns and is more essential. In this scenario, the proposal-based deep networks, like RCNN-series, often produce unsatisfactory results, because both the proposal extraction and classification stages may be confused by the irrelevant occluders. To address this, [25] proposed a voting mechanism that combines multiple local visual cues to detect semantic parts. The semantic parts can still be detected even though some visual cues are missing due to occlusions. However, this method is manually-designed, thus is hard to be optimized in an end-to-end manner. 
 In this paper, we present DeepVoting, which incorporates the robustness shown by [25] into a deep network, so that the whole pipeline can be jointly optimized. Specifically, it adds two layers after the intermediate features of a deep network, e.g., the pool-4 layer of VGGNet. The first layer extracts the evidence of local visual cues, and the second layer performs a voting mechanism by utilizing the spatial relationship between visual cues and semantic parts. We also propose an improved version DeepVoting+ by learning visual cues from context outside objects. In experiments, DeepVoting achieves significantly better performance than several baseline methods, including Faster-RCNN, for semantic part detection under occlusion. In addition, DeepVoting enjoys explainability as the detection results can be diagnosed via looking up the voting cues.

##### Abstract (translated by Google)
在本文中，我们研究在部分遮挡下检测物体的语义部分的任务，例如汽车的轮子。我们建议所有的模型都应该在没有看到遮挡的情况下进行培训，同时能够传输学到的知识来处理遮挡。该设置缓解了收集指数型大数据集以覆盖遮挡模式的困难，并且更为重要。在这种情况下，基于建议的深层网络（如RCNN系列）通常会产生令人不满意的结果，因为提案提取和分类阶段可能会被不相关的遮挡物混淆。为了解决这个问题，[25]提出了一种投票机制，它结合了多个局部视觉线索来检测语义部分。即使由于遮挡导致某些视觉线索丢失，语义部分仍然可以被检测到。然而，这种方法是手动设计的，因此很难以端对端的方式进行优化。
 在本文中，我们介绍DeepVoting，它将[25]所示的鲁棒性结合到深度网络中，从而可以对整个管道进行联合优化。具体来说，它在深度网络的中间特征之后增加了两层，例如VGGNet的pool-4层。第一层提取局部视觉线索的证据，第二层利用视觉线索和语义部分之间的空间关系执行投票机制。我们还通过从对象外部的上下文中学习视觉线索来提出改进的版本DeepVoting +。在实验中，DeepVote比包括Faster-RCNN在内的几种基线方法在遮挡下的语义部分检测实现了显着更好的性能。此外，DeepVoting具有可解释性，因为检测结果可通过查找投票提示进行诊断。

##### URL
[http://arxiv.org/abs/1709.04577](http://arxiv.org/abs/1709.04577)

##### PDF
[http://arxiv.org/pdf/1709.04577](http://arxiv.org/pdf/1709.04577)

