---
layout: post
title: "Statistics of RGBD Images"
date: 2016-04-11 12:00:57
categories: arXiv_CV
tags: arXiv_CV
author: Dan Rosenbaum, Yair Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Cameras that can measure the depth of each pixel in addition to its color have become easily available and are used in many consumer products worldwide. Often the depth channel is captured at lower quality compared to the RGB channels and different algorithms have been proposed to improve the quality of the D channel given the RGB channels. Typically these approaches work by assuming that edges in RGB are correlated with edges in D. In this paper we approach this problem from the standpoint of natural image statistics. We obtain examples of high quality RGBD images from a computer graphics generated movie (MPI-Sintel) and we use these examples to compare different probabilistic generative models of RGBD image patches. We then use the generative models together with a degradation model and obtain a Bayes Least Squares (BLS) estimator of the D channel given the RGB channels. Our results show that learned generative models outperform the state-of-the-art in improving the quality of depth channels given the color channels in natural images even when training is performed on artificially generated images.

##### Abstract (translated by Google)
除了颜色之外，还可以测量每个像素的深度的相机已经变得容易获得，并被用于全球许多消费类产品中。与RGB信道相比，深度信道通常以较低的质量被捕获，并且已经提出了不同的算法来改善给定RGB信道的D信道的质量。通常，这些方法通过假定RGB中的边缘与D中的边缘相关来工作。在本文中，我们从自然图像统计的角度来看待这个问题。我们从计算机图形生成的电影（MPI-Sintel）中获得高质量RGBD图像的例子，并且我们使用这些例子来比较不同的RGBD图像块的概率生成模型。然后，我们使用生成模型和退化模型，并获得给定RGB通道的D通道的贝叶斯最小二乘（BLS）估计量。我们的研究结果表明，即使在人工生成的图像上进行训练时，学习的生成模型在提高自然图像中的色彩通道的深度通道质量方面的表现也优于现有技术。

##### URL
[https://arxiv.org/abs/1604.02902](https://arxiv.org/abs/1604.02902)

##### PDF
[https://arxiv.org/pdf/1604.02902](https://arxiv.org/pdf/1604.02902)

