---
layout: post
title: "DAFL: Data-Free Learning of Student Networks"
date: 2019-05-29 06:50:22
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Hanting Chen, Yunhe Wang, Chang Xu, Zhaohui Yang, Chuanjian Liu, Boxin Shi, Chunjing Xu, Chao Xu, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Learning portable neural networks is very essential for computer vision for the purpose that pre-trained heavy deep models can be well applied on edge devices such as mobile phones and micro sensors. Most existing deep neural network compression and speed-up methods are very effective for training compact deep models, when we can directly access the training dataset. However, training data for the given deep network are often unavailable due to some practice problems (e.g. privacy, legal issue, and transmission), and the architecture of the given network are also unknown except some interfaces. To this end, we propose a novel framework for training efficient deep neural networks by exploiting generative adversarial networks (GANs). To be specific, the pre-trained teacher networks are regarded as a fixed discriminator and the generator is utilized for derivating training samples which can obtain the maximum response on the discriminator. Then, an efficient network with smaller model size and computational complexity is trained using the generated data and the teacher network, simultaneously. Efficient student networks learned using the proposed Data-Free Learning (DAFL) method achieve 92.22% and 74.47% accuracies using ResNet-18 without any training data on the CIFAR-10 and CIFAR-100 datasets, respectively. Meanwhile, our student network obtains an 80.56% accuracy on the CelebA benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01186](http://arxiv.org/abs/1904.01186)

##### PDF
[http://arxiv.org/pdf/1904.01186](http://arxiv.org/pdf/1904.01186)

