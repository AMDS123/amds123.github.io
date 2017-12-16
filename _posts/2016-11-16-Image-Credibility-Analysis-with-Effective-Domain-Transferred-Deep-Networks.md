---
layout: post
title: "Image Credibility Analysis with Effective Domain Transferred Deep Networks"
date: 2016-11-16 15:45:19
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Transfer_Learning Classification Recognition
author: Zhiwei Jin, Juan Cao, Jiebo Luo, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous fake images spread on social media today and can severely jeopardize the credibility of online content to public. In this paper, we employ deep networks to learn distinct fake image related features. In contrast to authentic images, fake images tend to be eye-catching and visually striking. Compared with traditional visual recognition tasks, it is extremely challenging to understand these psychologically triggered visual patterns in fake images. Traditional general image classification datasets, such as ImageNet set, are designed for feature learning at the object level but are not suitable for learning the hyper-features that would be required by image credibility analysis. In order to overcome the scarcity of training samples of fake images, we first construct a large-scale auxiliary dataset indirectly related to this task. This auxiliary dataset contains 0.6 million weakly-labeled fake and real images collected automatically from social media. Through an AdaBoost-like transfer learning algorithm, we train a CNN model with a few instances in the target training set and 0.6 million images in the collected auxiliary set. This learning algorithm is able to leverage knowledge from the auxiliary set and gradually transfer it to the target task. Experiments on a real-world testing set show that our proposed domain transferred CNN model outperforms several competing baselines. It obtains superiror results over transfer learning methods based on the general ImageNet set. Moreover, case studies show that our proposed method reveals some interesting patterns for distinguishing fake and authentic images.

##### Abstract (translated by Google)
无数假影像如今在社交媒体上传播，严重危害在线内容公开的可信度。在本文中，我们采用深度网络学习不同的假图像相关特征。与真实的图像相比，假图像往往引人注目，视觉效果惊人。与传统的视觉识别任务相比，了解这些虚假图像中的心理触发视觉模式是非常具有挑战性的。传统的一般图像分类数据集，如ImageNet集，被设计用于对象级别的特征学习，但不适合学习图像可信度分析所要求的超级特征。为了克服假图像训练样本的不足，我们首先构造一个与这个任务间接相关的大规模辅助数据集。这个辅助数据集包含60万个弱标记的虚假和真实的图像，从社交媒体自动收集。通过一种AdaBoost式的转移学习算法，我们训练一个CNN模型，在目标训练集中有几个实例，在收集的辅助集合中有60万个图像。该学习算法能够利用辅助集合中的知识并逐渐将其转移到目标任务。在现实世界的测试集上的实验表明，我们提出的域转移CNN模型胜过了几个竞争基线。它在基于一般ImageNet集的转移学习方法上获得了较好的结果。此外，案例研究表明，我们提出的方法揭示了一些有趣的模式来区分伪造和真实的图像。

##### URL
[https://arxiv.org/abs/1611.05328](https://arxiv.org/abs/1611.05328)

##### PDF
[https://arxiv.org/pdf/1611.05328](https://arxiv.org/pdf/1611.05328)

