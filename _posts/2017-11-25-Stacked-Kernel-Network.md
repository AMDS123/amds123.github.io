---
layout: post
title: "Stacked Kernel Network"
date: 2017-11-25 09:01:40
categories: arXiv_CV
tags: arXiv_CV CNN
author: Shuai Zhang, Jianxin Li, Pengtao Xie, Yingchun Zhang, Minglai Shao, Haoyi Zhou, Mengyi Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Kernel methods are powerful tools to capture nonlinear patterns behind data. They implicitly learn high (even infinite) dimensional nonlinear features in the Reproducing Kernel Hilbert Space (RKHS) while making the computation tractable by leveraging the kernel trick. Classic kernel methods learn a single layer of nonlinear features, whose representational power may be limited. Motivated by recent success of deep neural networks (DNNs) that learn multi-layer hierarchical representations, we propose a Stacked Kernel Network (SKN) that learns a hierarchy of RKHS-based nonlinear features. SKN interleaves several layers of nonlinear transformations (from a linear space to a RKHS) and linear transformations (from a RKHS to a linear space). Similar to DNNs, a SKN is composed of multiple layers of hidden units, but each parameterized by a RKHS function rather than a finite-dimensional vector. We propose three ways to represent the RKHS functions in SKN: (1)nonparametric representation, (2)parametric representation and (3)random Fourier feature representation. Furthermore, we expand SKN into CNN architecture called Stacked Kernel Convolutional Network (SKCN). SKCN learning a hierarchy of RKHS-based nonlinear features by convolutional operation with each filter also parameterized by a RKHS function rather than a finite-dimensional matrix in CNN, which is suitable for image inputs. Experiments on various datasets demonstrate the effectiveness of SKN and SKCN, which outperform the competitive methods.

##### Abstract (translated by Google)
内核方法是捕捉数据背后的非线性模式的强大工具。它们隐含地学习了再生核Hilbert空间（RKHS）中的高（甚至无限）维非线性特征，同时利用内核技巧使得计算易于处理。经典的内核方法学习单层非线性特征，其代表能力可能是有限的。最近在学习多层分层表示的深度神经网络（DNNs）的成功推动下，我们提出了一个学习基于RKHS的非线性特征层次结构的堆叠核心网络（SKN）。 SKN交织几层非线性变换（从线性空间到RKHS）和线性变换（从RKHS到线性空间）。类似于DNN，SKN由多层隐藏单元组成，但是每个由RKHS函数而不是有限维矢量来参数化。我们提出三种方法来表示SKN中的RKHS函数：（1）非参数表示，（2）参数表示和（3）随机傅立叶特征表示。此外，我们将SKN扩展到称为堆叠核心卷积网络（SKCN）的CNN架构。 SKCN通过卷积运算学习基于RKHS的非线性特征的层次结构，每个滤波器也由RKHS函数参数化而不是CNN中的有限维矩阵，其适合于图像输入。在各种数据集上的实验证明了SKN和SKCN的有效性，其胜过竞争方法。

##### URL
[https://arxiv.org/abs/1711.09219](https://arxiv.org/abs/1711.09219)

##### PDF
[https://arxiv.org/pdf/1711.09219](https://arxiv.org/pdf/1711.09219)

