---
layout: post
title: "Deep Deformable Registration: Enhancing Accuracy by Fully Convolutional Neural Net"
date: 2016-11-27 06:41:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sayan Ghosal, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Deformable registration is ubiquitous in medical image analysis. Many deformable registration methods minimize sum of squared difference (SSD) as the registration cost with respect to deformable model parameters. In this work, we construct a tight upper bound of the SSD registration cost by using a fully convolutional neural network (FCNN) in the registration pipeline. The upper bound SSD (UB-SSD) enhances the original deformable model parameter space by adding a heatmap output from FCNN. Next, we minimize this UB-SSD by adjusting both the parameters of the FCNN and the parameters of the deformable model in coordinate descent. Our coordinate descent framework is end-to-end and can work with any deformable registration method that uses SSD. We demonstrate experimentally that our method enhances the accuracy of deformable registration algorithms significantly on two publicly available 3D brain MRI data sets.

##### Abstract (translated by Google)
可变形的配准在医学图像分析中是无处不在的。许多可变形的配准方法使可变形模型参数的差值平方和（SSD）最小化为注册成本。在这项工作中，我们通过在注册管道中使用完全卷积神经网络（FCNN）构建SSD注册成本的紧上界。上界SSD（UB-SSD）通过添加FCNN的热图输出来增强原始可变形模型参数空间。接下来，我们通过在坐标下降中调整FCNN的参数和可变形模型的参数来最小化该UB-SSD。我们的坐标下降框架是端到端的，并且可以使用任何使用SSD的可变形注册方法。我们通过实验证明，我们的方法在两个公开可用的3D脑MRI数据集上显着提高了可变形配准算法的准确性。

##### URL
[https://arxiv.org/abs/1611.08796](https://arxiv.org/abs/1611.08796)

##### PDF
[https://arxiv.org/pdf/1611.08796](https://arxiv.org/pdf/1611.08796)

