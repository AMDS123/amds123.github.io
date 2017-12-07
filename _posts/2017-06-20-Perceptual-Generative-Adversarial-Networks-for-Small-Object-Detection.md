---
layout: post
title: "Perceptual Generative Adversarial Networks for Small Object Detection"
date: 2017-06-20 14:38:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Detection
author: Jianan Li, Xiaodan Liang, Yunchao Wei, Tingfa Xu, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting small objects is notoriously challenging due to their low resolution and noisy representation. Existing object detection pipelines usually detect small objects through learning representations of all the objects at multiple scales. However, the performance gain of such ad hoc architectures is usually limited to pay off the computational cost. In this work, we address the small object detection problem by developing a single architecture that internally lifts representations of small objects to "super-resolved" ones, achieving similar characteristics as large objects and thus more discriminative for detection. For this purpose, we propose a new Perceptual Generative Adversarial Network (Perceptual GAN) model that improves small object detection through narrowing representation difference of small objects from the large ones. Specifically, its generator learns to transfer perceived poor representations of the small objects to super-resolved ones that are similar enough to real large objects to fool a competing discriminator. Meanwhile its discriminator competes with the generator to identify the generated representation and imposes an additional perceptual requirement - generated representations of small objects must be beneficial for detection purpose - on the generator. Extensive evaluations on the challenging Tsinghua-Tencent 100K and the Caltech benchmark well demonstrate the superiority of Perceptual GAN in detecting small objects, including traffic signs and pedestrians, over well-established state-of-the-arts.

##### Abstract (translated by Google)
由于它们的分辨率低和噪声表示，检测小物体是非常具有挑战性的。现有的物体检测管线通常通过学习多个尺度上的所有物体的表示来检测小物体。然而，这样的特定体系结构的性能增益通常仅限于支付计算成本。在这项工作中，我们通过开发一种内部提升小物体表示为“超分辨”的单一架构来解决小物体检测问题，实现了与大物体类似的特性，从而更有针对性地进行检测。为此，本文提出了一种新的感知生成对抗网络（Perceptual Generative Adversarial Network，Perceptual GAN）模型，通过缩小小对象与大对象之间的表示差异来改善小对象检测。具体来说，它的生成器学习将小的对象的感知不良表示转移到超分辨的表示，这些表示与真实的大对象相似足以欺骗竞争的鉴别器。同时，它的鉴别器与发生器竞争以识别生成的表示并施加额外的感知要求 - 生成的小物体表示必须对发现者有利于检测目的。对具有挑战性的清华 - 腾讯100K和加州理工基准进行广泛的评估，充分证明了感知型GAN在检测小型物体（包括交通标志和行人）方面的优越性。

##### URL
[https://arxiv.org/abs/1706.05274](https://arxiv.org/abs/1706.05274)

##### PDF
[https://arxiv.org/pdf/1706.05274](https://arxiv.org/pdf/1706.05274)

