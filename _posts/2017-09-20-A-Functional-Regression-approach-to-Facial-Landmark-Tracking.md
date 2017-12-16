---
layout: post
title: "A Functional Regression approach to Facial Landmark Tracking"
date: 2017-09-20 15:58:32
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Tracking Detection Face_Detection
author: Enrique Sánchez-Lozano, Georgios Tzimiropoulos, Brais Martinez, Fernando De la Torre, Michel Valstar
mathjax: true
---

* content
{:toc}

##### Abstract
Linear regression is a fundamental building block in many face detection and tracking algorithms, typically used to predict shape displacements from image features through a linear mapping. This paper presents a Functional Regression solution to the least squares problem, which we coin Continuous Regression, resulting in the first real-time incremental face tracker. Contrary to prior work in Functional Regression, in which B-splines or Fourier series were used, we propose to approximate the input space by its first-order Taylor expansion, yielding a closed-form solution for the continuous domain of displacements. We then extend the continuous least squares problem to correlated variables, and demonstrate the generalisation of our approach. We incorporate Continuous Regression into the cascaded regression framework, and show its computational benefits for both training and testing. We then present a fast approach for incremental learning within Cascaded Continuous Regression, coined iCCR, and show that its complexity allows real-time face tracking, being 20 times faster than the state of the art. To the best of our knowledge, this is the first incremental face tracker that is shown to operate in real-time. We show that iCCR achieves state-of-the-art performance on the 300-VW dataset, the most recent, large-scale benchmark for face tracking.

##### Abstract (translated by Google)
线性回归是许多人脸检测和跟踪算法的基本构建模块，通常用于通过线性映射来预测图像特征的形状位移。本文提出了一个最小二乘问题的函数回归解决方案，我们投币连续回归，导致第一个实时增量人脸跟踪器。与之前在函数回归中使用B样条或傅里叶级数的工作相反，我们提出通过其一阶泰勒展开来逼近输入空间，从而产生连续的位移域的封闭形式解。然后，我们将连续最小二乘问题扩展到相关变量，并展示了我们方法的推广。我们将连续回归结合到级联回归框架中，并显示其对培训和测试的计算收益。然后，我们提出了一种快速的级联连续回归渐进式学习方法，创造了iCCR，并表明其复杂性允许实时面孔跟踪，比现有技术快20倍。据我们所知，这是第一个实时操作的面部追踪器。我们展示了iCCR在300VW数据集上实现了最新的性能，这是最新的大规模人脸跟踪基准。

##### URL
[https://arxiv.org/abs/1612.02203](https://arxiv.org/abs/1612.02203)

##### PDF
[https://arxiv.org/pdf/1612.02203](https://arxiv.org/pdf/1612.02203)

