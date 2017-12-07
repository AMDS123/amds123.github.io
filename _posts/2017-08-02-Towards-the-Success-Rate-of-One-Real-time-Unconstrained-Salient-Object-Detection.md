---
layout: post
title: "Towards the Success Rate of One: Real-time Unconstrained Salient Object Detection"
date: 2017-08-02 05:22:48
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Inference Prediction Detection
author: Mahyar Najibi, Fan Yang, Qiaosong Wang, Robinson Piramuthu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose an efficient and effective approach for unconstrained salient object detection in images using deep convolutional neural networks. Instead of generating thousands of candidate bounding boxes and refining them, our network directly learns to generate the saliency map containing the exact number of salient objects. During training, we convert the ground-truth rectangular boxes to Gaussian distributions that better capture the ROI regarding individual salient objects. During inference, the network predicts Gaussian distributions centered at salient objects with an appropriate covariance, from which bounding boxes are easily inferred. Notably, our network performs saliency map prediction without pixel-level annotations, salient object detection without object proposals, and salient object subitizing simultaneously, all in a single pass within a unified framework. Extensive experiments show that our approach outperforms existing methods on various datasets by a large margin, and achieves more than 100 fps with VGG16 network on a single GPU during inference.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个高效率和有效的方法为无约束显着对象检测图像使用深度卷积神经网络。我们的网络不是生成数以千计的候选边界框并对其进行细化，而是直接学习生成包含确切数量的显着对象的显着图。在训练期间，我们将地面实况矩形框转换为高斯分布，以更好地捕捉关于各个显着对象的ROI。在推断过程中，网络预测高斯分布以显着物体为中心，具有适当的协方差，从而容易推断边界框。值得注意的是，我们的网络在没有像素级注释的情况下执行显着性图预测，没有对象提议的显着对象检测，以及在统一框架内一次通过的显着对象同时子图化。大量的实验表明，我们的方法大大优于现有的各种数据集的方法，在推理过程中，单GPU上的VGG16网络达到100 fps以上。

##### URL
[https://arxiv.org/abs/1708.00079](https://arxiv.org/abs/1708.00079)

##### PDF
[https://arxiv.org/pdf/1708.00079](https://arxiv.org/pdf/1708.00079)

