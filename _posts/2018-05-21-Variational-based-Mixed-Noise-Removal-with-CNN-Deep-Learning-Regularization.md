---
layout: post
title: "Variational based Mixed Noise Removal with CNN Deep Learning Regularization"
date: 2018-05-21 14:52:06
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Classification Deep_Learning
author: Faqiang Wang, Haiyang Huang, Jun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, the traditional model based variational method and learning based algorithms are naturally integrated to address mixed noise removal problem. To be different from single type noise (e.g. Gaussian) removal, it is a challenge problem to accurately discriminate noise types and levels for each pixel. We propose a variational method to iteratively estimate the noise parameters, and then the algorithm can automatically classify the noise according to the different statistical parameters. The proposed variational problem can be separated into regularization, synthesis, parameter estimation and noise classification four steps with the operator splitting scheme. Each step is related to an optimization subproblem. To enforce the regularization, the deep learning method is employed to learn the natural images priori. Compared with some model based regularizations, the CNN regularizer can significantly improve the quality of the restored images. Compared with some learning based methods, the synthesis step can produce better reconstructions by analyzing the recognized noise types and levels. In our method, the convolution neutral network (CNN) can be regarded as an operator which associated to a variational functional. From this viewpoint, the proposed method can be extended to many image reconstruction and inverse problems. Numerical experiments in the paper show that our method can achieve some state-of-the-art results for mixed noise removal.

##### Abstract (translated by Google)
本文将传统的基于模型的变分方法和基于学习的算法自然地结合起来，以解决混合噪声去除问题。为了与单一类型的噪声（例如高斯）去除不同，精确地区分每个像素的噪声类型和级别是一个挑战性问题。我们提出了一种迭代估计噪声参数的变分方法，然后该算法可以根据不同的统计参数自动分类噪声。所提出的变分问题可以用算子分裂方案分为正则化，综合，参数估计和噪声分类四个步骤。每一步都与一个优化子问题有关。为了强化正则化，深度学习方法被用来先验地学习自然图像。与一些基于模型的正则化相比，CNN正则化算子可以显着提高恢复图像的质量。与一些基于学习的方法相比，合成步骤通过分析所识别的噪声类型和级别可以产生更好的重建。在我们的方法中，卷积中性网络（CNN）可以看作是与变分函数相关的算子。从这个角度来看，所提出的方法可以扩展到许多图像重建和反演问题。本文的数值实验表明，我们的方法可以实现混合噪声去除的一些最新技术成果。

##### URL
[https://arxiv.org/abs/1805.08094](https://arxiv.org/abs/1805.08094)

##### PDF
[https://arxiv.org/pdf/1805.08094](https://arxiv.org/pdf/1805.08094)

