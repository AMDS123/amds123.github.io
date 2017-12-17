---
layout: post
title: "Data Augmentation Generative Adversarial Networks"
date: 2017-11-12 19:17:57
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Antreas Antoniou, Amos Storkey, Harrison Edwards
mathjax: true
---

* content
{:toc}

##### Abstract
Effective training of neural networks requires much data. In the low-data regime, parameters are underdetermined, and learnt networks generalise poorly. Data Augmentation \cite{krizhevsky2012imagenet} alleviates this by using existing data more effectively. However standard data augmentation produces only limited plausible alternative data. Given there is potential to generate a much broader set of augmentations, we design and train a generative model to do data augmentation. The model, based on image conditional Generative Adversarial Networks, takes data from a source domain and learns to take any data item and generalise it to generate other within-class data items. As this generative process does not depend on the classes themselves, it can be applied to novel unseen classes of data. We show that a Data Augmentation Generative Adversarial Network (DAGAN) augments standard vanilla classifiers well. We also show a DAGAN can enhance few-shot learning systems such as Matching Networks. We demonstrate these approaches on Omniglot, on EMNIST having learnt the DAGAN on Omniglot, and VGG-Face data. In our experiments we can see over 13\% increase in accuracy in the low-data regime experiments in Omniglot (from 69\% to 82\%), EMNIST (73.9\% to 76\%) and VGG-Face (4.5\% to 12\%); in Matching Networks for Omniglot we observe an increase of 0.5\% (from 96.9\% to 97.4\%) and an increase of 1.8\% in EMNIST (from 59.5\% to 61.3\%).

##### Abstract (translated by Google)
神经网络的有效训练需要大量数据。在低数据情况下，参数不确定，学习网络泛化不良。数据增加\引用{krizhevsky2012imagenet}通过更有效地使用现有数据来减轻这一点。然而，标准的数据增加只会产生有限的似是而非的替代数据。考虑到有可能产生更广泛的增强，我们设计和训练一个生成模型来进行数据增强。该模型基于图像条件生成对抗网络，从源域获取数据，并学习获取任意数据项并将其推广以生成其他类内数据项。由于这个生成过程不依赖于类本身，它可以应用于新的看不见的类数据。我们表明，数据增强生成敌对网络（DAGAN）很好地增加了标准的香草分类器。我们还展示了一个DAGAN可以增强少数学习系统，如匹配网络。我们在Omniglot上演示了这些方法，在EMNIST上学习了Omniglot上的DAGAN和VGG-Face数据。在我们的实验中，我们可以看到在Omniglot（从69％到82％），EMNIST（73.9％到76％）和VGG-Face（4.5 \％）的低数据区域实验中精度提高了13％ ％到12 \％）;在Omniglot的匹配网络中，我们观察到EMNIST中的增加0.5％（从96.9％增加到97.4％）和增加1.8％（从59.5％增加到61.3％）。

##### URL
[https://arxiv.org/abs/1711.04340](https://arxiv.org/abs/1711.04340)

##### PDF
[https://arxiv.org/pdf/1711.04340](https://arxiv.org/pdf/1711.04340)

