---
layout: post
title: "Physics-based Learned Design: Optimized Coded-Illumination for Quantitative Phase Imaging"
date: 2018-08-10 14:58:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Quantitative
author: Michael R. Kellman, Emrah Bostan, Nicole Repina, Michael Lustig, Laura Waller
mathjax: true
---

* content
{:toc}

##### Abstract
Coded-illumination based reconstruction of Quantitative Phase (QP) is generally a non-linear iterative process. Thus, using traditional techniques for experimental design (e.g. condition number optimization or spectral analysis) may not be ideal as they characterize linear measurement formation models for linear reconstructions. Deep neural networks, DNNs, are end-to-end frameworks which can efficiently represent non-linear processes and can be optimized over by training. However, they do not necessarily include knowledge of the system physics and, as a result, require an enormous number of training examples and parameters to properly learn the phase retrieval process. Here, we present a new data-driven approach to optimize the coded-illumination patterns of a light-emitting diode (LED) array microscope to maximize a given QP reconstruction algorithm's performance. We establish a generalized formulation that incorporates the available information about the physics of a measurement model as well as the non-linearities of a reconstruction algorithm into the design problem. Our proposed design method enables an efficient parameterization of the design problem, which allows us to use only a small number of training examples to properly learn a design that generalizes well in the experimental setting without retraining. We image both a well-characterized phase target and mouse fibroblast cells using coded-illumination patterns optimized for a sparsity-based phase reconstruction algorithm. We obtain QP images similar to those of Fourier Ptychographic techniques with 69 measurements using only 2 learned design measurements.

##### Abstract (translated by Google)
基于编码照明的定量相位（QP）重建通常是非线性迭代过程。因此，使用传统技术进行实验设计（例如条件数优化或光谱分析）可能并不理想，因为它们表征线性重建的线性测量形成模型。深度神经网络（DNN）是端到端框架，可以有效地表示非线性过程，并且可以通过培训进行优化。但是，它们不一定包括系统物理知识，因此需要大量的训练样例和参数来正确学习相位检索过程。在这里，我们提出了一种新的数据驱动方法来优化发光二极管（LED）阵列显微镜的编码照明模式，以最大化给定的QP重建算法的性能。我们建立了一个通用公式，它将有关测量模型物理特性的可用信息以及重建算法的非线性结合到设计问题中。我们提出的设计方法能够有效地对设计问题进行参数化，这使我们只需使用少量的训练样例就可以正确地学习在没有再训练的情况下在实验环境中很好地概括的设计。我们使用针对基于稀疏性的相位重建算法优化的编码照明模式对充分表征的相位目标和小鼠成纤维细胞成像。我们获得了类似于傅里叶Ptychographic技术的QP图像，仅使用2个学习设计测量进行了69次测量。

##### URL
[http://arxiv.org/abs/1808.03571](http://arxiv.org/abs/1808.03571)

##### PDF
[http://arxiv.org/pdf/1808.03571](http://arxiv.org/pdf/1808.03571)

