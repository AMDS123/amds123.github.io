---
layout: post
title: "A volumetric deep Convolutional Neural Network for simulation of dark matter halo catalogues"
date: 2018-05-11 18:05:50
categories: arXiv_CV
tags: arXiv_CV Survey CNN Prediction
author: Philippe Berger, George Stein
mathjax: true
---

* content
{:toc}

##### Abstract
For modern large-scale structure survey techniques it has become standard practice to test data analysis pipelines on large suites of mock simulations, a task which is currently prohibitively expensive for full N-body simulations. Instead of calculating this costly gravitational evolution, we have trained a three-dimensional deep Convolutional Neural Network (CNN) to identify dark matter protohalos directly from the cosmological initial conditions. Training on halo catalogues from the Peak Patch semi-analytic code, we test various CNN architectures and find they generically achieve a Dice coefficient of ~92% in only 24 hours of training. We present a simple and fast geometric halo finding algorithm to extract halos from this powerful pixel-wise binary classifier and find that the predicted catalogues match the mass function and power spectra of the ground truth simulations to within ~10%. We investigate the effect of long-range tidal forces on an object-by-object basis and find that the network's predictions are consistent with the non-linear ellipsoidal collapse equations used explicitly by the Peak Patch algorithm.

##### Abstract (translated by Google)
对于现代大型结构测量技术来说，在大型模拟仿真套件上测试数据分析流水线已成为标准做法，这对于完全N体仿真而言目前非常昂贵。我们没有计算这种昂贵的引力演化，而是训练了一个三维深层卷积神经网络（CNN），从宇宙初始条件直接识别暗物质原始晕。我们对Peak Patch半分析代码中的光环目录进行了培训，我们测试了各种CNN体系结构，发现它们在24小时的训练中一般达到〜92％的Dice系数。我们提出了一种简单而快速的几何光晕发现算法，从这个强大的逐像素二进制分类器中提取光晕，并发现预测的目录将地面真实模拟的质量函数和功率谱匹配在〜10％之内。我们研究了远程潮汐力对逐个物体的影响，并发现网络的预测与Peak Patch算法明确使用的非线性椭球体崩溃方程一致。

##### URL
[https://arxiv.org/abs/1805.04537](https://arxiv.org/abs/1805.04537)

##### PDF
[https://arxiv.org/pdf/1805.04537](https://arxiv.org/pdf/1805.04537)

