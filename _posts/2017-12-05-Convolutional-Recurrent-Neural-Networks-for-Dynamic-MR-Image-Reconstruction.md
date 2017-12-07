---
layout: post
title: "Convolutional Recurrent Neural Networks for Dynamic MR Image Reconstruction"
date: 2017-12-05 16:49:07
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Relation
author: Chen Qin, Jo Schlemper, Jose Caballero, Anthony Price, Joseph V. Hajnal, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Accelerating the data acquisition of dynamic magnetic resonance imaging (MRI) leads to a challenging ill-posed inverse problem, which has received great interest from both the signal processing and machine learning community over the last decades. The key ingredient to the problem is how to exploit the temporal correlation of the MR sequence to resolve the aliasing artefact. Traditionally, such observation led to a formulation of a non-convex optimisation problem, which were solved using iterative algorithms. Recently, however, deep learning based-approaches have gained significant popularity due to its ability to solve general inversion problems. In this work, we propose a unique, novel convolutional recurrent neural network (CRNN) architecture which reconstructs high quality cardiac MR images from highly undersampled k-space data by jointly exploiting the dependencies of the temporal sequences as well as the iterative nature of the traditional optimisation algorithms. In particular, the proposed architecture embeds the structure of the traditional iterative algorithms, efficiently modelling the recurrence of the iterative reconstruction stages by using recurrent hidden connections over such iterations. In addition, spatiotemporal dependencies are simultaneously learnt by exploiting bidirectional recurrent hidden connections across time sequences. The proposed algorithm is able to learn both the temporal dependency and the iterative reconstruction process effectively with only a very small number of parameters, while outperforming current MR reconstruction methods in terms of computational complexity, reconstruction accuracy and speed.

##### Abstract (translated by Google)
加速动态磁共振成像（MRI）的数据采集导致了一个具有挑战性的不适定的反演问题，这在过去几十年已经引起了信号处理和机器学习界的极大兴趣。该问题的关键是如何利用MR序列的时间相关性来解决混叠伪像。传统上，这样的观察导致了非凸优化问题的表述，这些问题使用迭代算法来解决。然而，最近，由于深度学习方法能够解决一般的反演问题，因此深受学习者欢迎。在这项工作中，我们提出了独特的，新颖的卷积递归神经网络（CRNN）架构，通过联合利用时间序列的依赖性以及传统的迭代本质，从高度欠采样的k-空间数据重建高质量的心脏MR图像优化算法。具体而言，所提出的架构嵌入传统迭代算法的结构，通过在迭代中使用循环隐藏连接来高效地建模迭代重建阶段的重现。另外，通过利用跨时间序列的双向循环隐藏连接同时学习时空依赖性。该算法能够有效地学习时间依赖性和迭代重建过程，只需要很少的参数，同时在计算复杂度，重构精度和速度方面优于目前的MR重建方法。

##### URL
[https://arxiv.org/abs/1712.01751](https://arxiv.org/abs/1712.01751)

##### PDF
[https://arxiv.org/pdf/1712.01751](https://arxiv.org/pdf/1712.01751)

