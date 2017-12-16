---
layout: post
title: "Temporal 3D ConvNets: New Architecture and Transfer Learning for Video Classification"
date: 2017-11-22 10:01:37
categories: arXiv_CV
tags: arXiv_CV Knowledge Action_Recognition CNN Transfer_Learning Video_Classification Classification Recognition
author: Ali Diba, Mohsen Fayyaz, Vivek Sharma, Amir Hossein Karami, Mohammad Mahdi Arzani, Rahman Yousefzadeh, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
The work in this paper is driven by the question how to exploit the temporal cues available in videos for their accurate classification, and for human action recognition in particular? Thus far, the vision community has focused on spatio-temporal approaches with fixed temporal convolution kernel depths. We introduce a new temporal layer that models variable temporal convolution kernel depths. We embed this new temporal layer in our proposed 3D CNN. We extend the DenseNet architecture - which normally is 2D - with 3D filters and pooling kernels. We name our proposed video convolutional network `Temporal 3D ConvNet'~(T3D) and its new temporal layer `Temporal Transition Layer'~(TTL). Our experiments show that T3D outperforms the current state-of-the-art methods on the HMDB51, UCF101 and Kinetics datasets. The other issue in training 3D ConvNets is about training them from scratch with a huge labeled dataset to get a reasonable performance. So the knowledge learned in 2D ConvNets is completely ignored. Another contribution in this work is a simple and effective technique to transfer knowledge from a pre-trained 2D CNN to a randomly initialized 3D CNN for a stable weight initialization. This allows us to significantly reduce the number of training samples for 3D CNNs. Thus, by finetuning this network, we beat the performance of generic and recent methods in 3D CNNs, which were trained on large video datasets, e.g. Sports-1M, and finetuned on the target datasets, e.g. HMDB51/UCF101. The T3D codes will be released

##### Abstract (translated by Google)
本文的工作是由如何利用视频中的时间线索进行精确分类以及特别是如何识别人类行为所驱动的？到目前为止，视觉社区已经集中在具有固定时间卷积核深度的时空方法上。我们引入一个新的时间层，模拟可变时间卷积核深度。我们在我们提出的3D CNN中嵌入了这个新的时间层。 DenseNet体系结构（通常是2D）通过3D滤镜和内核池来扩展。我们命名我们提出的视频卷积网络“时间三维ConvNet”〜（T3D）及其新的时间层“时间转换层”〜（TTL）。我们的实验显示，T3D优于HMDB51，UCF101和动力学数据集上当前最先进的方法。培训3D ConvNets的另一个问题是关于用一个巨大的标签数据集从头开始对它们进行培训以获得合理的性能。所以在2D ConvNets中学到的知识是完全被忽略的。这项工作的另一个贡献是一个简单而有效的技术，将知识从预先训练的二维CNN转移到一个随机初始化的3D CNN，以实现稳定的重量初始化。这使我们能够显着减少3D CNN的训练样本数量。因此，通过微调这个网络，我们击败了在大型视频数据集上训练的3D CNN中的通用和最近方法的性能，例如， Sports-1M，并在目标数据集上进行调整，例如HMDB51 / UCF101。 T3D代码将被释放

##### URL
[https://arxiv.org/abs/1711.08200](https://arxiv.org/abs/1711.08200)

##### PDF
[https://arxiv.org/pdf/1711.08200](https://arxiv.org/pdf/1711.08200)

