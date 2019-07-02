---
layout: post
title: "ComDefend: An Efficient Image Compression Model to Defend Adversarial Examples"
date: 2019-07-01 13:04:25
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Xiaojun Jia, Xingxing Wei, Xiaochun Cao, Hassan Foroosh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have been demonstrated to be vulnerable to adversarial examples. Specifically, adding imperceptible perturbations to clean images can fool the well trained deep neural networks. In this paper, we propose an end-to-end image compression model to defend adversarial examples: \textbf{ComDefend}. The proposed model consists of a compression convolutional neural network (ComCNN) and a reconstruction convolutional neural network (ResCNN). The ComCNN is used to maintain the structure information of the original image and purify adversarial perturbations. And the ResCNN is used to reconstruct the original image with high quality. In other words, ComDefend can transform the adversarial image to its clean version, which is then fed to the trained classifier. Our method is a pre-processing module, and does not modify the classifier's structure during the whole process. Therefore, it can be combined with other model-specific defense models to jointly improve the classifier's robustness. A series of experiments conducted on MNIST, CIFAR10 and ImageNet show that the proposed method outperforms the state-of-the-art defense methods, and is consistently effective to protect classifiers against adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12673](http://arxiv.org/abs/1811.12673)

##### PDF
[http://arxiv.org/pdf/1811.12673](http://arxiv.org/pdf/1811.12673)

