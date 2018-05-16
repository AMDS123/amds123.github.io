---
layout: post
title: "ShapeCodes: Self-Supervised Feature Learning by Lifting Views to Viewgrids"
date: 2018-05-15 04:17:28
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Recognition
author: Dinesh Jayaraman, Ruohan Gao, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an unsupervised feature learning approach that embeds 3D shape information into a single-view image representation. The main idea is a self-supervised training objective that, given only a single 2D image, requires all unseen views of the object to be predictable from learned features. We implement this idea as an encoder-decoder convolutional neural network. The network maps an input image of an unknown category and unknown viewpoint to a latent space, from which a deconvolutional decoder can best "lift" the image to its complete viewgrid showing the object from all viewing angles. Our class-agnostic training procedure encourages the representation to capture fundamental shape primitives and semantic regularities in a data-driven manner---without manual semantic labels. Our results on two widely-used shape datasets show 1) our approach successfully learns to perform "mental rotation" even for objects unseen during training, and 2) the learned latent space is a powerful representation for object recognition, outperforming several existing unsupervised feature learning methods.

##### Abstract (translated by Google)
我们介绍一种无监督的特征学习方法，将3D形状信息嵌入到单视图图像表示中。主要思想是一个自我监督的训练目标，只给定一个2D图像，要求从学习的特征中可以预测出该对象的所有看不见的视图。我们将这个想法实现为编码器 - 解码器卷积神经网络。网络将未知类别和未知视点的输入图像映射到潜在空间，解卷积解码器可以从该空间将图像最佳地“提升”到其从所有视角显示对象的完整视图网格。我们的类不可知的训练过程鼓励表示以数据驱动的方式捕捉基本的形状原语和语义规则 - 没有人工语义标签。我们在两个广泛使用的形状数据集上的结果显示：1）即使对于训练期间看不见的物体，我们的方法也能成功地进行“心理旋转”; 2）学习的潜在空间是目标识别的强大表示，优于几个现有的无监督特征学习方法。

##### URL
[http://arxiv.org/abs/1709.00505](http://arxiv.org/abs/1709.00505)

##### PDF
[http://arxiv.org/pdf/1709.00505](http://arxiv.org/pdf/1709.00505)

