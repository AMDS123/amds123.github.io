---
layout: post
title: "Semi and Weakly Supervised Semantic Segmentation Using Generative Adversarial Network"
date: 2017-03-28 17:57:21
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Weakly_Supervised GAN Semantic_Segmentation Classification
author: Nasim Souly, Concetto Spampinato, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation has been a long standing challenging task in computer vision. It aims at assigning a label to each image pixel and needs significant number of pixellevel annotated data, which is often unavailable. To address this lack, in this paper, we leverage, on one hand, massive amount of available unlabeled or weakly labeled data, and on the other hand, non-real images created through Generative Adversarial Networks. In particular, we propose a semi-supervised framework ,based on Generative Adversarial Networks (GANs), which consists of a generator network to provide extra training examples to a multi-class classifier, acting as discriminator in the GAN framework, that assigns sample a label y from the K possible classes or marks it as a fake sample (extra class). The underlying idea is that adding large fake visual data forces real samples to be close in the feature space, enabling a bottom-up clustering process, which, in turn, improves multiclass pixel classification. To ensure higher quality of generated images for GANs with consequent improved pixel classification, we extend the above framework by adding weakly annotated data, i.e., we provide class level information to the generator. We tested our approaches on several challenging benchmarking visual datasets, i.e. PASCAL, SiftFLow, Stanford and CamVid, achieving competitive performance also compared to state-of-the-art semantic segmentation method

##### Abstract (translated by Google)
语义分割一直是计算机视觉领域一个长期的挑战。它旨在为每个图像像素分配一个标签，并且需要大量的像素级注释数据，这通常是不可用的。为了解决这个问题，在本文中，我们一方面利用大量可用的未标记或弱标记数据，另一方面利用生成敌对​​网络创建的非真实图像。具体来说，我们提出了一个基于生成对抗网络（GAN）的半监督框架，它由一个生成器网络组成，为多类分类器提供额外的训练样例，作为GAN框架中的判别器，标注来自K个可能类的y或将其标记为假样本（额外的类）。其基本思想是添加大量的虚拟视觉数据，迫使真实样本在特征空间中靠近，从而实现自下而上的聚类过程，从而改善多类像素分类。为了保证GAN生成的图像具有更高的质量，从而改善像素分类，我们通过添加弱注释数据来扩展上述框架，即向生成器提供类级别信息。我们测试了几种具有挑战性的基准视觉数据集（即PASCAL，SiftFLow，Stanford和CamVid）的方法，与最先进的语义分割方法

##### URL
[https://arxiv.org/abs/1703.09695](https://arxiv.org/abs/1703.09695)

##### PDF
[https://arxiv.org/pdf/1703.09695](https://arxiv.org/pdf/1703.09695)

