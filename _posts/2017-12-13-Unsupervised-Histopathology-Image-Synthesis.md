---
layout: post
title: "Unsupervised Histopathology Image Synthesis"
date: 2017-12-13 21:52:12
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN
author: Le Hou, Ayush Agarwal, Dimitris Samaras, Tahsin M. Kurc, Rajarsi R. Gupta, Joel H. Saltz
mathjax: true
---

* content
{:toc}

##### Abstract
Hematoxylin and Eosin stained histopathology image analysis is essential for the diagnosis and study of complicated diseases such as cancer. Existing state-of-the-art approaches demand extensive amount of supervised training data from trained pathologists. In this work we synthesize in an unsupervised manner, large histopathology image datasets, suitable for supervised training tasks. We propose a unified pipeline that: a) generates a set of initial synthetic histopathology images with paired information about the nuclei such as segmentation masks; b) refines the initial synthetic images through a Generative Adversarial Network (GAN) to reference styles; c) trains a task-specific CNN and boosts the performance of the task-specific CNN with on-the-fly generated adversarial examples. Our main contribution is that the synthetic images are not only realistic, but also representative (in reference styles) and relatively challenging for training task-specific CNNs. We test our method for nucleus segmentation using images from four cancer types. When no supervised data exists for a cancer type, our method without supervision cost significantly outperforms supervised methods which perform across-cancer generalization. Even when supervised data exists for all cancer types, our approach without supervision cost performs better than supervised methods.

##### Abstract (translated by Google)
苏木精和伊红染色的组织病理学图像分析对于诸如癌症的复杂疾病的诊断和研究是必不可少的。现有的最先进的方法需要来自训练有素的病理学家的大量监督训练数据。在这项工作中，我们以无监督的方式合成大型组织病理学图像数据集，适合有监督的训练任务。我们提出了一个统一的流水线：a）生成一组初始的合成组织病理学图像，其中包含关于细胞核的配对信息，例如分割掩模; b）通过生成敌对网络（GAN）将初始合成图像细化为参考样式; c）训练一个特定于任务的CNN，并利用即时生成的敌对示例提高特定于任务的CNN的性能。我们的主要贡献是合成图像不仅是现实的，而且还有代表性（参考样式）和相对具有挑战性的训练任务特定的CNNs。我们使用来自四种癌症类型的图像来测试我们的细胞核分割方法。当没有监督数据存在的癌症类型，我们的方法没有监督成本显着优于监督方法执行跨癌症泛化。即使监督数据存在所有的癌症类型，我们的方法没有监督成本表现好于监督方法。

##### URL
[http://arxiv.org/abs/1712.05021](http://arxiv.org/abs/1712.05021)

##### PDF
[http://arxiv.org/pdf/1712.05021](http://arxiv.org/pdf/1712.05021)

