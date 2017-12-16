---
layout: post
title: "On Data-Driven Saak Transform"
date: 2017-10-14 17:40:37
categories: arXiv_CV
tags: arXiv_CV Classification Relation Recognition
author: C.-C. Jay Kuo, Yueru Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Being motivated by the multilayer RECOS (REctified-COrrelations on a Sphere) transform, we develop a data-driven Saak (Subspace approximation with augmented kernels) transform in this work. The Saak transform consists of three steps: 1) building the optimal linear subspace approximation with orthonormal bases using the second-order statistics of input vectors, 2) augmenting each transform kernel with its negative, 3) applying the rectified linear unit (ReLU) to the transform output. The Karhunen-Lo\'eve transform (KLT) is used in the first step. The integration of Steps 2 and 3 is powerful since they resolve the sign confusion problem, remove the rectification loss and allow a straightforward implementation of the inverse Saak transform at the same time. Multiple Saak transforms are cascaded to transform images of a larger size. All Saak transform kernels are derived from the second-order statistics of input random vectors in a one-pass feedforward manner. Neither data labels nor backpropagation is used in kernel determination. Multi-stage Saak transforms offer a family of joint spatial-spectral representations between two extremes; namely, the full spatial-domain representation and the full spectral-domain representation. We select Saak coefficients of higher discriminant power to form a feature vector for pattern recognition, and use the MNIST dataset classification problem as an illustrative example.

##### Abstract (translated by Google)
受到多层RECOS（球面上的REctified-COrrelations）变换的启发，我们开发了一个数据驱动的Saak（子空间近似与增广内核）变换。 Saak变换包括三个步骤：1）使用输入向量的二阶统计量，用正交基构建最优线性子空间近似; 2）用负数扩大每个变换核; 3）将整形线性单元（ReLU）应用于转换输出。 Karhunen-Loeve变换（KLT）被用于第一步。步骤2和步骤3的整合是强大的，因为它们解决了符号混淆问题，消除了整流损失，并允许同时直接执行反向Saak变换。多个Saak变换级联以转换较大尺寸的图像。所有的Saak变换核都是通过单向前馈方式从输入随机向量的二阶统计中推导出来的。内核确定中不使用数据标签也不使用反向传播。多级Saak变换提供了两个极端之间的联合空间谱表示族;即完整的空间域表示和完整的频谱域表示。我们选择较高判别能力的Saak系数形成模式识别的特征向量，并以MNIST数据集分类问题为例进行说明。

##### URL
[https://arxiv.org/abs/1710.04176](https://arxiv.org/abs/1710.04176)

##### PDF
[https://arxiv.org/pdf/1710.04176](https://arxiv.org/pdf/1710.04176)

