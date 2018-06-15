---
layout: post
title: "ReConvNet: Video Object Segmentation with Spatio-Temporal Features Modulation"
date: 2018-06-14 12:52:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference
author: Francesco Lattari, Marco Ciccone, Matteo Matteucci, Jonathan Masci, Francesco Visin
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce ReConvNet, a recurrent convolutional architecture for semi-supervised video object segmentation that is able to fast adapt its features to focus on the object of interest at inference time. Generalizing to new objects not observed during training is known to be an hard task for supervised approaches that need to be retrained on the new instances. To tackle this problem, we propose a more efficient solution that learns spatio-temporal features that can be adapted by the model itself through affine transformations conditioned on the object in the first frame of the sequence. This approach is simple, it can be trained end-to-end and does not require extra training steps at inference time. Our method shows comparable results on DAVIS2016 with respect to state-of-the art approaches that use online finetuning, and outperform them on DAVIS2017. ReConvNet shows also promising results on the DAVIS-Challenge 2018 placing in $10$-th position.

##### Abstract (translated by Google)
我们介绍了ReConvNet，一种用于半监督视频对象分割的递归卷积体系结构，能够快速调整其特征，以便在推理时聚焦于感兴趣的对象。已知在训练期间未观察到的新对象被认为是需要在新实例上进行再训练的受监督方法的艰巨任务。为了解决这个问题，我们提出了一个更有效的解决方案，该方案学习时空特征，可以通过仿射变换对模型本身进行调整，以对序列的第一帧中的对象进行调节。这种方法很简单，可以进行端对端培训，并且不需要在推理时进行额外的培训。我们的方法在DAVIS2016上显示了与使用在线微调有关的最新技术方法的可比较结果，并在DAVIS2017上表现优于其他方法。 ReConvNet在DAVIS-Challenge 2018展会上也取得了令人满意的成果，并以$ 10 $的价格排名。

##### URL
[http://arxiv.org/abs/1806.05510](http://arxiv.org/abs/1806.05510)

##### PDF
[http://arxiv.org/pdf/1806.05510](http://arxiv.org/pdf/1806.05510)

