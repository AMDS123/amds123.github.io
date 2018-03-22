---
layout: post
title: "Unsupervised Representation Learning by Predicting Image Rotations"
date: 2018-03-21 03:21:14
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Represenation_Learning Classification Quantitative Detection
author: Spyros Gidaris, Praveer Singh, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
Over the last years, deep convolutional neural networks (ConvNets) have transformed the field of computer vision thanks to their unparalleled capacity to learn high level semantic image features. However, in order to successfully learn those features, they usually require massive amounts of manually labeled data, which is both expensive and impractical to scale. Therefore, unsupervised semantic feature learning, i.e., learning without requiring manual annotation effort, is of crucial importance in order to successfully harvest the vast amount of visual data that are available today. In our work we propose to learn image features by training ConvNets to recognize the 2d rotation that is applied to the image that it gets as input. We demonstrate both qualitatively and quantitatively that this apparently simple task actually provides a very powerful supervisory signal for semantic feature learning. We exhaustively evaluate our method in various unsupervised feature learning benchmarks and we exhibit in all of them state-of-the-art performance. Specifically, our results on those benchmarks demonstrate dramatic improvements w.r.t. prior state-of-the-art approaches in unsupervised representation learning and thus significantly close the gap with supervised feature learning. For instance, in PASCAL VOC 2007 detection task our unsupervised pre-trained AlexNet model achieves the state-of-the-art (among unsupervised methods) mAP of 54.4% that is only 2.4 points lower from the supervised case. We get similarly striking results when we transfer our unsupervised learned features on various other tasks, such as ImageNet classification, PASCAL classification, PASCAL segmentation, and CIFAR-10 classification. The code and models of our paper will be published on: https://github.com/gidariss/FeatureLearningRotNet .

##### Abstract (translated by Google)
在过去的几年中，深卷积神经网络（ConvNets）已经改变了计算机视觉领域，这要归功于它们无与伦比的学习高级语义图像特征的能力。但是，为了成功学习这些功能，他们通常需要大量手动标记的数据，这既昂贵又不切实际。因此，无监督的语义特征学习，即不需要手动注释努力的学习，对于成功收获当今可用的大量视觉数据至关重要。在我们的工作中，我们建议通过训练ConvNets来识别应用于它作为输入的图像的二维旋转来学习图像特征。我们从定性和定量两个方面展示了这个看似简单的任务实际上为语义特征学习提供了一个非常强大的监督信号。我们在各种无监督的特征学习基准中对我们的方法进行了详尽的评估，并且我们展示了其中所有最先进的性能。具体来说，我们在这些基准测试中的结果显示了w.r.t的显着提升。先前在无监督表示学习中的先进方法，从而显着缩小与监督特征学习的差距。例如，在PASCAL VOC 2007检测任务中，我们的无监督预先训练的AlexNet模型达到了54.4％的最新技术水平（无监督方法中），仅比监督案例低2.4个百分点。当我们将我们的无监督学习特征转移到ImageNet分类，PASCAL分类，PASCAL分割和CIFAR-10分类等各种其他任务上时，我们也获得了类似的惊人结果。我们论文的代码和模型将发布在：https：//github.com/gidariss/FeatureLearningRotNet。

##### URL
[http://arxiv.org/abs/1803.07728](http://arxiv.org/abs/1803.07728)

##### PDF
[http://arxiv.org/pdf/1803.07728](http://arxiv.org/pdf/1803.07728)

