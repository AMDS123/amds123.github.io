---
layout: post
title: "Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization"
date: 2017-07-30 09:32:17
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Optimization
author: Xun Huang, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Gatys et al. recently introduced a neural algorithm that renders a content image in the style of another image, achieving so-called style transfer. However, their framework requires a slow iterative optimization process, which limits its practical application. Fast approximations with feed-forward neural networks have been proposed to speed up neural style transfer. Unfortunately, the speed improvement comes at a cost: the network is usually tied to a fixed set of styles and cannot adapt to arbitrary new styles. In this paper, we present a simple yet effective approach that for the first time enables arbitrary style transfer in real-time. At the heart of our method is a novel adaptive instance normalization (AdaIN) layer that aligns the mean and variance of the content features with those of the style features. Our method achieves speed comparable to the fastest existing approach, without the restriction to a pre-defined set of styles. In addition, our approach allows flexible user controls such as content-style trade-off, style interpolation, color & spatial controls, all using a single feed-forward neural network.

##### Abstract (translated by Google)
Gatys等人最近引入了一种神经算法，使内容图像呈现另一个图像的风格，实现所谓的风格转移。然而，他们的框架需要一个缓慢的迭代优化过程，这限制了它的实际应用。已经提出用前馈神经网络的快速近似来加速神经样式转移。不幸的是，速度的提高要付出代价：网络通常绑定到一套固定的样式，不能适应任意的新样式。在本文中，我们提出了一个简单而有效的方法，它首次实现了任意样式的传输。我们方法的核心是一个新颖的自适应实例规范化（AdaIN）层，它将内容特征的均值和方差与样式特征的均值和方差对齐。我们的方法实现了速度与现有最快的方法相媲美，而不受限于预先定义的一组样式。此外，我们的方法允许灵活的用户控制，如内容式的权衡，样式插值，颜色和空间控制，所有这些都使用一个前馈神经网络。

##### URL
[https://arxiv.org/abs/1703.06868](https://arxiv.org/abs/1703.06868)

##### PDF
[https://arxiv.org/pdf/1703.06868](https://arxiv.org/pdf/1703.06868)

