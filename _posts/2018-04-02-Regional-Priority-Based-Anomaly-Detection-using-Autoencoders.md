---
layout: post
title: "Regional Priority Based Anomaly Detection using Autoencoders"
date: 2018-04-02 13:49:01
categories: arXiv_AI
tags: arXiv_AI Object_Detection Semi_Supervised CNN Detection
author: Shruti Mittal, Dattaraj Rao
mathjax: true
---

* content
{:toc}

##### Abstract
In the recent times, autoencoders, besides being used for compression, have been proven quite useful even for regenerating similar images or help in image denoising. They have also been explored for anomaly detection in a few cases. However, due to location invariance property of convolutional neural network, autoencoders tend to learn from or search for learned features in the complete image. This creates issues when all the items in the image are not equally important and their location matters. For such cases, a semi supervised solution - regional priority based autoencoder (RPAE) has been proposed. In this model, similar to object detection models, a region proposal network identifies the relevant areas in the images as belonging to one of the predefined categories and then those bounding boxes are fed into appropriate decoder based on the category they belong to. Finally, the error scores from all the decoders are combined based on their importance to provide total reconstruction error.

##### Abstract (translated by Google)
在最近的时代，自动编码器除了用于压缩之外，已经被证明是非常有用的，即使对于再生类似的图像或帮助图像去噪。在少数情况下，它们也被用于异常检测。然而，由于卷积神经网络的位置不变性，自动编码器倾向于从完整图像中学习或搜索学习特征。这会在图像中的所有项目不同等重要并且位置很重要时产生问题。对于这样的情况，已经提出了半监督解决方案 - 基于区域优先级的自动编码器（RPAE）。在该模型中，与对象检测模型类似，区域提议网络将图像中的相关区域标识为属于预定义类别之一，然后根据它们所属的类别将这些边界框馈送到适当的解码器中。最后，根据所有解码器的错误分数的重要性来提供总重建误差。

##### URL
[http://arxiv.org/abs/1804.00492](http://arxiv.org/abs/1804.00492)

##### PDF
[http://arxiv.org/pdf/1804.00492](http://arxiv.org/pdf/1804.00492)

