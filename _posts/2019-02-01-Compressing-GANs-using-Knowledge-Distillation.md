---
layout: post
title: "Compressing GANs using Knowledge Distillation"
date: 2019-02-01 03:24:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Knowledge GAN Optimization Gradient_Descent
author: Angeline Aguinaldo, Ping-Yeh Chiang, Alex Gain, Ameya Patil, Kolten Pearson, Soheil Feizi
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have been used in several machine learning tasks such as domain transfer, super resolution, and synthetic data generation. State-of-the-art GANs often use tens of millions of parameters, making them expensive to deploy for applications in low SWAP (size, weight, and power) hardware, such as mobile devices, and for applications with real time capabilities. There has been no work found to reduce the number of parameters used in GANs. Therefore, we propose a method to compress GANs using knowledge distillation techniques, in which a smaller "student" GAN learns to mimic a larger "teacher" GAN. We show that the distillation methods used on MNIST, CIFAR-10, and Celeb-A datasets can compress teacher GANs at ratios of 1669:1, 58:1, and 87:1, respectively, while retaining the quality of the generated image. From our experiments, we observe a qualitative limit for GAN's compression. Moreover, we observe that, with a fixed parameter budget, compressed GANs outperform GANs trained using standard training methods. We conjecture that this is partially owing to the optimization landscape of over-parameterized GANs which allows efficient training using alternating gradient descent. Thus, training an over-parameterized GAN followed by our proposed compression scheme provides a high quality generative model with a small number of parameters.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.00159](https://arxiv.org/abs/1902.00159)

##### PDF
[https://arxiv.org/pdf/1902.00159](https://arxiv.org/pdf/1902.00159)

