---
layout: post
title: "Accurate Image Super-Resolution Using Very Deep Convolutional Networks"
date: 2016-11-11 08:40:47
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Classification
author: Jiwon Kim, Jung Kwon Lee, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a highly accurate single-image super-resolution (SR) method. Our method uses a very deep convolutional network inspired by VGG-net used for ImageNet classification \cite{simonyan2015very}. We find increasing our network depth shows a significant improvement in accuracy. Our final model uses 20 weight layers. By cascading small filters many times in a deep network structure, contextual information over large image regions is exploited in an efficient way. With very deep networks, however, convergence speed becomes a critical issue during training. We propose a simple yet effective training procedure. We learn residuals only and use extremely high learning rates ($10^4$ times higher than SRCNN \cite{dong2015image}) enabled by adjustable gradient clipping. Our proposed method performs better than existing methods in accuracy and visual improvements in our results are easily noticeable.

##### Abstract (translated by Google)
我们提出了一个高度准确的单图像超分辨率（SR）的方法。我们的方法使用了一个非常深的卷积网络，受VGG-net的启发，用于ImageNet分类\ cite {simonyan2015very}。我们发现增加我们的网络深度显示了准确性的显着提高。我们的最终模型使用20个重量层。通过在深度网络结构中多次级联小型过滤器，高效率地利用大型图像区域上下文信息。然而，网络非常深，收敛速度成为培训中的关键问题。我们提出一个简单而有效的培训程序。我们只学习残差，并使用可调渐变裁剪实现的极高学习率（比SRCNN \ cite {dong2015image}高$ 10 ^ 4 $倍）。我们提出的方法比现有的方法在精确性方面表现更好，而且我们的结果的视觉改善也很容易察觉。

##### URL
[https://arxiv.org/abs/1511.04587](https://arxiv.org/abs/1511.04587)

##### PDF
[https://arxiv.org/pdf/1511.04587](https://arxiv.org/pdf/1511.04587)

