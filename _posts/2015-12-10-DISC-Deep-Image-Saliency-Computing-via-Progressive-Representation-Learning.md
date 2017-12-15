---
layout: post
title: "DISC: Deep Image Saliency Computing via Progressive Representation Learning"
date: 2015-12-10 13:11:23
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Attention CNN Represenation_Learning Detection Recognition
author: Tianshui Chen, Liang Lin, Lingbo Liu, Xiaonan Luo, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Salient object detection increasingly receives attention as an important component or step in several pattern recognition and image processing tasks. Although a variety of powerful saliency models have been intensively proposed, they usually involve heavy feature (or model) engineering based on priors (or assumptions) about the properties of objects and backgrounds. Inspired by the effectiveness of recently developed feature learning, we provide a novel Deep Image Saliency Computing (DISC) framework for fine-grained image saliency computing. In particular, we model the image saliency from both the coarse- and fine-level observations, and utilize the deep convolutional neural network (CNN) to learn the saliency representation in a progressive manner. Specifically, our saliency model is built upon two stacked CNNs. The first CNN generates a coarse-level saliency map by taking the overall image as the input, roughly identifying saliency regions in the global context. Furthermore, we integrate superpixel-based local context information in the first CNN to refine the coarse-level saliency map. Guided by the coarse saliency map, the second CNN focuses on the local context to produce fine-grained and accurate saliency map while preserving object details. For a testing image, the two CNNs collaboratively conduct the saliency computing in one shot. Our DISC framework is capable of uniformly highlighting the objects-of-interest from complex background while preserving well object details. Extensive experiments on several standard benchmarks suggest that DISC outperforms other state-of-the-art methods and it also generalizes well across datasets without additional training. The executable version of DISC is available online: this http URL

##### Abstract (translated by Google)
显着物体检测作为多个模式识别和图像处理任务中的重要组件或步骤日益受到关注。虽然各种强大的显着性模型已经被深入的提出，但是它们通常涉及基于关于对象和背景的属性的先验（或假设）的重特征（或模型）工程。受到最近开发的特征学习的有效性的启发，我们提供了一个新颖的深度图像显着性计算（DISC）框架，用于精细图像显着性计算。具体而言，我们从粗糙和精细的观测数据中对图像显着性进行建模，并利用深度卷积神经网络（CNN）以渐进方式学习显着性表示。具体而言，我们的显着性模型建立在两个叠加的CNN上。第一个CNN通过把整个图像作为输入生成一个粗糙的显着图，粗略地识别全局上下文中的显着性区域。此外，我们在第一个CNN中集成了基于超像素的本地上下文信息来细化粗糙级显着图。在粗糙显着图的引导下，第二CNN侧重于局部上下文，在保留对象细节的同时产生细粒度，准确的显着图。对于测试图像来说，这两个CNN一起合作进行显着性计算。我们的DISC框架能够从复杂的背景中一致地突出显示感兴趣的对象，同时保持良好的对象细节。对几个标准基准进行广泛的实验表明，DISC比其他最先进的方法优越，并且在没有额外训练的情况下，也可以在数据集之间很好地推广。 DISC的可执行版本可以在线获得：http http

##### URL
[https://arxiv.org/abs/1511.04192](https://arxiv.org/abs/1511.04192)

##### PDF
[https://arxiv.org/pdf/1511.04192](https://arxiv.org/pdf/1511.04192)

