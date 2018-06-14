---
layout: post
title: "Self-Supervised Feature Learning by Learning to Spot Artifacts"
date: 2018-06-13 13:24:42
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Simon Jenni, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel self-supervised learning method based on adversarial training. Our objective is to train a discriminator network to distinguish real images from images with synthetic artifacts, and then to extract features from its intermediate layers that can be transferred to other data domains and tasks. To generate images with artifacts, we pre-train a high-capacity autoencoder and then we use a damage and repair strategy: First, we freeze the autoencoder and damage the output of the encoder by randomly dropping its entries. Second, we augment the decoder with a repair network, and train it in an adversarial manner against the discriminator. The repair network helps generate more realistic images by inpainting the dropped feature entries. To make the discriminator focus on the artifacts, we also make it predict what entries in the feature were dropped. We demonstrate experimentally that features learned by creating and spotting artifacts achieve state of the art performance in several benchmarks.

##### Abstract (translated by Google)
我们引入了一种新的基于对抗训练的自监督学习方法。我们的目标是训练一个鉴别器网络，将真实图像与合成伪像的图像区分开来，然后从其中间层提取可转移到其他数据域和任务的特征。为了生成带有伪像的图像，我们预训练一个高容量的自动编码器，然后使用损坏和修复策略：首先，我们冻结自动编码器并通过随机丢弃其条目来损坏编码器的输出。其次，我们通过修复网络增强解码器，并以对立的方式训练它对抗鉴别器。修复网络通过修复丢弃的特征条目来帮助生成更逼真的图像。为了使鉴别器专注于工件，我们还使它能够预测该特征中的哪些条目被丢弃。我们通过实验证明，通过创建和发现工件来学习的特征能够在几个基准测试中实现最先进的性能。

##### URL
[http://arxiv.org/abs/1806.05024](http://arxiv.org/abs/1806.05024)

##### PDF
[http://arxiv.org/pdf/1806.05024](http://arxiv.org/pdf/1806.05024)

