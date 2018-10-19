---
layout: post
title: "KTAN: Knowledge Transfer Adversarial Network"
date: 2018-10-18 15:57:02
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Knowledge CNN Image_Classification Classification Detection Relation
author: Peiye Liu, Wu Liu, Huadong Ma, Tao Mei, Mingoo Seok
mathjax: true
---

* content
{:toc}

##### Abstract
To reduce the large computation and storage cost of a deep convolutional neural network, the knowledge distillation based methods have pioneered to transfer the generalization ability of a large (teacher) deep network to a light-weight (student) network. However, these methods mostly focus on transferring the probability distribution of the softmax layer in a teacher network and thus neglect the intermediate representations. In this paper, we propose a knowledge transfer adversarial network to better train a student network. Our technique holistically considers both intermediate representations and probability distributions of a teacher network. To transfer the knowledge of intermediate representations, we set high-level teacher feature maps as a target, toward which the student feature maps are trained. Specifically, we arrange a Teacher-to-Student layer for enabling our framework suitable for various student structures. The intermediate representation helps the student network better understand the transferred generalization as compared to the probability distribution only. Furthermore, we infuse an adversarial learning process by employing a discriminator network, which can fully exploit the spatial correlation of feature maps in training a student network. The experimental results demonstrate that the proposed method can significantly improve the performance of a student network on both image classification and object detection tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.08126](https://arxiv.org/abs/1810.08126)

##### PDF
[https://arxiv.org/pdf/1810.08126](https://arxiv.org/pdf/1810.08126)

