---
layout: post
title: "Good Features to Correlate for Visual Tracking"
date: 2018-03-10 12:43:55
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Classification Deep_Learning Relation
author: Erhan Gundogdu, A. Aydin Alatan
mathjax: true
---

* content
{:toc}

##### Abstract
During the recent years, correlation filters have shown dominant and spectacular results for visual object tracking. The types of the features that are employed in these family of trackers significantly affect the performance of visual tracking. The ultimate goal is to utilize robust features invariant to any kind of appearance change of the object, while predicting the object location as properly as in the case of no appearance change. As the deep learning based methods have emerged, the study of learning features for specific tasks has accelerated. For instance, discriminative visual tracking methods based on deep architectures have been studied with promising performance. Nevertheless, correlation filter based (CFB) trackers confine themselves to use the pre-trained networks which are trained for object classification problem. To this end, in this manuscript the problem of learning deep fully convolutional features for the CFB visual tracking is formulated. In order to learn the proposed model, a novel and efficient backpropagation algorithm is presented based on the loss function of the network. The proposed learning framework enables the network model to be flexible for a custom design. Moreover, it alleviates the dependency on the network trained for classification. Extensive performance analysis shows the efficacy of the proposed custom design in the CFB tracking framework. By fine-tuning the convolutional parts of a state-of-the-art network and integrating this model to a CFB tracker, which is the top performing one of VOT2016, 18% increase is achieved in terms of expected average overlap, and tracking failures are decreased by 25%, while maintaining the superiority over the state-of-the-art methods in OTB-2013 and OTB-2015 tracking datasets.

##### Abstract (translated by Google)
在近年来，相关滤波器已经显示出对于视觉对象跟踪的主导和壮观的结果。这些跟踪器系列中使用的功能的类型显着影响视觉跟踪的性能。最终目标是利用对物体的任何外观变化都不变的鲁棒特征，同时预测物体的位置，就像在没有外观变化的情况下一样。随着基于深度学习的方法的出现，针对特定任务的学习特征的研究加速了。例如，基于深度体系结构的判别式视觉跟踪方法已经被研究并具有令人满意的性能。然而，基于相关滤波器（CFB）的跟踪器局限于使用训练好的用于目标分类问题的预训练网络。为此，在本手稿中，为CFB视觉跟踪学习了深度完全卷积特征的学习问题。为了学习所提出的模型，基于网络的损失函数提出了一种新的高效的反向传播算法。所提出的学习框架使得网络模型对于定制设计而言是灵活的。此外，它减轻了对分类训练网络的依赖。广泛的性能分析显示了建议的定制设计在CFB跟踪框架中的功效。通过对最先进的网络的卷积部分进行微调，并将该模型与VOT2016中性能最好的CFB跟踪器相集成，预期的平均重叠增加了18％，跟踪失败比OTB-2013和OTB-2015跟踪数据集中的最先进方法的优越性降低了25％。

##### URL
[http://arxiv.org/abs/1704.06326](http://arxiv.org/abs/1704.06326)

##### PDF
[http://arxiv.org/pdf/1704.06326](http://arxiv.org/pdf/1704.06326)

