---
layout: post
title: "Appearance-Based 3D Gaze Estimation with Personal Calibration"
date: 2018-07-02 13:59:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Erik Lind&#xe9;n, Jonas Sj&#xf6;strand, Alexandre Proutiere
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a way to incorporate personal calibration into a deep learning model for video-based gaze estimation. Using our method, we show that by calibrating six parameters per person, accuracy can be improved by a factor of 2.2 to 2.5. The number of personal parameters, three per eye, is similar to the number predicted by geometrical models. When evaluated on the MPIIGaze dataset, our estimator performs better than person-specific estimators. To improve generalization, we predict gaze rays in 3D (origin and direction of gaze). In existing datasets, the 3D gaze is underdetermined, since all gaze targets are in the same plane as the camera. Experiments on synthetic data suggest it would be possible to learn accurate 3D gaze from only annotated gaze targets, without annotated eye positions.

##### Abstract (translated by Google)
我们提出了一种将个人校准结合到基于视频的凝视估计的深度学习模型中的方法。使用我们的方法，我们证明通过每人校准六个参数，精度可以提高2.2到2.5倍。个人参数的数量，每只眼睛三个，与几何模型预测的数量相似。在MPIIGaze数据集上进行评估时，我们的估算器的性能优于人员特定的估算器。为了改善泛化，我们预测3D中的凝视射线（凝视的起源和方向）。在现有数据集中，3D凝视是不确定的，因为所有凝视目标与摄像机在同一平面中。对合成数据的实验表明，只有注释的凝视目标才能学习准确的3D凝视，而没有注释的眼睛位置。

##### URL
[http://arxiv.org/abs/1807.00664](http://arxiv.org/abs/1807.00664)

##### PDF
[http://arxiv.org/pdf/1807.00664](http://arxiv.org/pdf/1807.00664)

