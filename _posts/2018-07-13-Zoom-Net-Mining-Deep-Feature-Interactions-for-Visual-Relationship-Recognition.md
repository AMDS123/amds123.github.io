---
layout: post
title: "Zoom-Net: Mining Deep Feature Interactions for Visual Relationship Recognition"
date: 2018-07-13 09:20:39
categories: arXiv_CV
tags: arXiv_CV Image_Caption Relation Recognition
author: Guojun Yin, Lu Sheng, Bin Liu, Nenghai Yu, Xiaogang Wang, Jing Shao, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing visual relationships &lt;subject-predicate-object&gt; among any pair of localized objects is pivotal for image understanding. Previous studies have shown remarkable progress in exploiting linguistic priors or external textual information to improve the performance. In this work, we investigate an orthogonal perspective based on feature interactions. We show that by encouraging deep message propagation and interactions between local object features and global predicate features, one can achieve compelling performance in recognizing complex relationships without using any linguistic priors. To this end, we present two new pooling cells to encourage feature interactions: (i) Contrastive ROI Pooling Cell, which has a unique deROI pooling that inversely pools local object features to the corresponding area of global predicate features. (ii) Pyramid ROI Pooling Cell, which broadcasts global predicate features to reinforce local object features.The two cells constitute a Spatiality-Context-Appearance Module (SCA-M), which can be further stacked consecutively to form our final Zoom-Net.We further shed light on how one could resolve ambiguous and noisy object and predicate annotations by Intra-Hierarchical trees (IH-tree). Extensive experiments conducted on Visual Genome dataset demonstrate the effectiveness of our feature-oriented approach compared to state-of-the-art methods (Acc@1 11.42% from 8.16%) that depend on explicit modeling of linguistic interactions. We further show that SCA-M can be incorporated seamlessly into existing approaches to improve the performance by a large margin. The source code will be released on https://github.com/gjyin91/ZoomNet.

##### Abstract (translated by Google)
识别视觉关系＆lt; subject-predicate-object＆gt;在任何一对本地化对象中，对于图像理解至关重要。以前的研究表明，在利用语言先验或外部文本信息来改善绩效方面取得了显着进展。在这项工作中，我们研究了基于特征相互作用的正交透视图。我们通过鼓励深度消息传播以及本地对象特征与全局谓词特征之间的交互，表明在不使用任何语言先验的情况下识别复杂关系可以获得令人信服的性能。为此，我们提出了两个新的池化单元来鼓励特征交互：（i）对比ROI池化单元，它具有唯一的deROI池，将本地对象特征反向汇集到全局谓词特征的相应区域。 （ii）金字塔ROI Pooling Cell，它广播全局谓词特征以强化本地对象特征。这两个单元构成一个空间 - 上下文 - 外观模块（SCA-M），可以进一步连续堆叠以形成我们的最终Zoom-Net。我们进一步阐明了如何通过Intra-Hierarchical树（IH-tree）来解决模糊和嘈杂的对象以及谓词注释。在Visual Genome数据集上进行的大量实验证明，与最先进的方法（Acc @ 1 11.42％，8.16％）相比，我们的面向特征的方法的有效性依赖于语言交互的显式建模。我们进一步表明，SCA-M可以无缝地整合到现有方法中，以大幅提高性能。源代码将在https://github.com/gjyin91/ZoomNet上发布。

##### URL
[http://arxiv.org/abs/1807.04979](http://arxiv.org/abs/1807.04979)

##### PDF
[http://arxiv.org/pdf/1807.04979](http://arxiv.org/pdf/1807.04979)

