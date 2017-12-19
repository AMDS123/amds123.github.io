---
layout: post
title: "Learning High-level Prior with Convolutional Neural Networks for Semantic Segmentation"
date: 2015-11-22 10:25:02
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Optimization Recognition
author: Haitian Zheng, Yebin Liu, Mengqi Ji, Feng Wu, Lu Fang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a convolutional neural network that can fuse high-level prior for semantic image segmentation. Motivated by humans' vision recognition system, our key design is a three-layer generative structure consisting of high-level coding, middle-level segmentation and low-level image to introduce global prior for semantic segmentation. Based on this structure, we proposed a generative model called conditional variational auto-encoder (CVAE) that can build up the links behind these three layers. These important links include an image encoder that extracts high level info from image, a segmentation encoder that extracts high level info from segmentation, and a hybrid decoder that outputs semantic segmentation from the high level prior and input image. We theoretically derive the semantic segmentation as an optimization problem parameterized by these links. Finally, the optimization problem enables us to take advantage of state-of-the-art fully convolutional network structure for the implementation of the above encoders and decoder. Experimental results on several representative datasets demonstrate our supreme performance for semantic segmentation.

##### Abstract (translated by Google)
本文提出一种卷积神经网络，可以融合高层次的语义图像分割。受到人类视觉识别系统的启发，我们的关键设计是一个由高层次编码，中间层次分割和低层次图像组成的三层生成结构，引入全局的语义分割。基于这种结构，我们提出了一种称为条件变分自编码器（CVAE）的生成模型，可以建立这三层之间的链路。这些重要的链接包括从图像中提取高级信息的图像编码器，从分割中提取高级信息的分割编码器，以及从高级先前输入图像输出语义分割的混合解码器。我们从理论上推导出语义分割作为这些链接参数化的优化问题。最后，优化问题使我们能够利用最先进的完全卷积网络结构来实现上述编码器和解码器。对几个有代表性的数据集的实验结果证明了我们在语义分割方面的最高性能。

##### URL
[https://arxiv.org/abs/1511.06988](https://arxiv.org/abs/1511.06988)

##### PDF
[https://arxiv.org/pdf/1511.06988](https://arxiv.org/pdf/1511.06988)

