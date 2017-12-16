---
layout: post
title: "Looking Beyond Appearances: Synthetic Training Data for Deep CNNs in Re-identification"
date: 2017-01-11 20:43:41
categories: arXiv_CV
tags: arXiv_CV Re-identification CNN
author: Igor Barros Barbosa, Marco Cristani, Barbara Caputo, Aleksander Rognhaugen, Theoharis Theoharis
mathjax: true
---

* content
{:toc}

##### Abstract
Re-identification is generally carried out by encoding the appearance of a subject in terms of outfit, suggesting scenarios where people do not change their attire. In this paper we overcome this restriction, by proposing a framework based on a deep convolutional neural network, SOMAnet, that additionally models other discriminative aspects, namely, structural attributes of the human figure (e.g. height, obesity, gender). Our method is unique in many respects. First, SOMAnet is based on the Inception architecture, departing from the usual siamese framework. This spares expensive data preparation (pairing images across cameras) and allows the understanding of what the network learned. Second, and most notably, the training data consists of a synthetic 100K instance dataset, SOMAset, created by photorealistic human body generation software. Synthetic data represents a good compromise between realistic imagery, usually not required in re-identification since surveillance cameras capture low-resolution silhouettes, and complete control of the samples, which is useful in order to customize the data w.r.t. the surveillance scenario at-hand, e.g. ethnicity. SOMAnet, trained on SOMAset and fine-tuned on recent re-identification benchmarks, outperforms all competitors, matching subjects even with different apparel. The combination of synthetic data with Inception architectures opens up new research avenues in re-identification.

##### Abstract (translated by Google)
重新识别通常是通过在服装方面对主体的外观进行编码来进行的，提示人们不换衣服的情况。在本文中，我们通过提出基于深层卷积神经网络SOMAnet的框架来克服这个限制，该框架另外对其他区别性方面，即人体结构属性（例如身高，肥胖，性别）进行建模。我们的方法在很多方面都是独一无二的。首先，SOMAnet基于初始架构，从通常的连体框架出发。这节省了昂贵的数据准备工作（在摄像机之间配对图像），并可以帮助您了解网络学到的内容。其次，最值得注意的是，训练数据由一个合成的100K实例数据集SOMAset组成，这个数据集由照片级人体生成软件创建。合成数据代表了实际图像之间的良好折衷，通常在重新识别中不需要重新识别，因为监视摄像机捕获低分辨率的轮廓，并且完全控制样本，这对于定制数据w.r.t是有用的。手边的监控场景，例如种族。 SOMAnet对SOMAset进行了培训，并对最近的重新识别基准进行了精细调整，胜过所有竞争对手，甚至与不同的服装相匹配。合成数据与初始结构的结合为重新鉴定开辟了新的研究途径。

##### URL
[https://arxiv.org/abs/1701.03153](https://arxiv.org/abs/1701.03153)

##### PDF
[https://arxiv.org/pdf/1701.03153](https://arxiv.org/pdf/1701.03153)

