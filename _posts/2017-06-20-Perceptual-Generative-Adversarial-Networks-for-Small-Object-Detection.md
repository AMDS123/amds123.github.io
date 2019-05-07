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


##### URL
[https://arxiv.org/abs/1706.05274](https://arxiv.org/abs/1706.05274)

##### PDF
[https://arxiv.org/pdf/1706.05274](https://arxiv.org/pdf/1706.05274)

