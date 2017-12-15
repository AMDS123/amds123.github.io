---
layout: post
title: "Texture Modelling with Nested High-order Markov-Gibbs Random Fields"
date: 2015-10-08 15:22:21
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Ralph Versteegen, Georgy Gimel'farb, Patricia Riddle
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, Markov-Gibbs random field (MGRF) image models which include high-order interactions are almost always built by modelling responses of a stack of local linear filters. Actual interaction structure is specified implicitly by the filter coefficients. In contrast, we learn an explicit high-order MGRF structure by considering the learning process in terms of general exponential family distributions nested over base models, so that potentials added later can build on previous ones. We relatively rapidly add new features by skipping over the costly optimisation of parameters. We introduce the use of local binary patterns as features in MGRF texture models, and generalise them by learning offsets to the surrounding pixels. These prove effective as high-order features, and are fast to compute. Several schemes for selecting high-order features by composition or search of a small subclass are compared. Additionally we present a simple modification of the maximum likelihood as a texture modelling-specific objective function which aims to improve generalisation by local windowing of statistics. The proposed method was experimentally evaluated by learning high-order MGRF models for a broad selection of complex textures and then performing texture synthesis, and succeeded on much of the continuum from stochastic through irregularly structured to near-regular textures. Learning interaction structure is very beneficial for textures with large-scale structure, although those with complex irregular structure still provide difficulties. The texture models were also quantitatively evaluated on two tasks and found to be competitive with other works: grading of synthesised textures by a panel of observers; and comparison against several recent MGRF models by evaluation on a constrained inpainting task.

##### Abstract (translated by Google)
目前，包含高阶相互作用的马尔可夫 - 吉布斯随机场（MGRF）图像模型几乎总是通过建立一堆局部线性滤波器的响应来建立的。实际的交互结构由滤波器系数隐式指定。相比之下，我们学习一个显式的高阶MGRF结构，通过考虑基于模型的一般指数族分布的学习过程，以便后面添加的潜能可以建立在以前的基础上。我们通过跳过参数的昂贵优化来相对快速地添加新功能。我们介绍使用局部二进制模式作为MGRF纹理模型中的特征，并通过学习到周围像素的偏移量来推广它们。这些证明是有效的高阶特征，并且计算速度快。比较了几种通过构图或搜索小类来选择高阶特征的方案。此外，我们提出了一个简单的最大似然修改，作为一个纹理建模特定的目标函数，旨在通过统计局部窗口来改善泛化。所提出的方法是通过学习高阶MGRF模型对复杂纹理进行广泛选择，然后进行纹理合成来进行实验评估，并在从随机到非规则结构到近似正则纹理的连续体中取得了成功。学习交互结构对于具有大规模结构的纹理是非常有利的，但是具有复杂的不规则结构的结构仍然存在困难。对纹理模型也进行了两个任务的定量评估，发现与其他作品相比具有竞争力：一组观察者对合成纹理进行分级;并通过对受约束修复任务的评估与最近的几个MGRF模型进行比较。

##### URL
[https://arxiv.org/abs/1510.02364](https://arxiv.org/abs/1510.02364)

##### PDF
[https://arxiv.org/pdf/1510.02364](https://arxiv.org/pdf/1510.02364)

