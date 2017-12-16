---
layout: post
title: "Learning Joint Feature Adaptation for Zero-Shot Recognition"
date: 2016-12-03 03:17:02
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Ziming Zhang, Venkatesh Saligrama
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot recognition (ZSR) aims to recognize target-domain data instances of unseen classes based on the models learned from associated pairs of seen-class source and target domain data. One of the key challenges in ZSR is the relative scarcity of source-domain features (e.g. one feature vector per class), which do not fully account for wide variability in target-domain instances. In this paper we propose a novel framework of learning data-dependent feature transforms for scoring similarity between an arbitrary pair of source and target data instances to account for the wide variability in target domain. Our proposed approach is based on optimizing over a parameterized family of local feature displacements that maximize the source-target adaptive similarity functions. Accordingly we propose formulating zero-shot learning (ZSL) using latent structural SVMs to learn our similarity functions from training data. As demonstration we design a specific algorithm under the proposed framework involving bilinear similarity functions and regularized least squares as penalties for feature displacement. We test our approach on several benchmark datasets for ZSR and show significant improvement over the state-of-the-art. For instance, on aP&Y dataset we can achieve 80.89% in terms of recognition accuracy, outperforming the state-of-the-art by 11.15%.

##### Abstract (translated by Google)
零点识别（ZSR）旨在基于从关联的已知类别的源和目标域数据中学习到的模型来识别未见类的目标域数据实例。 ZSR中的关键挑战之一是源域特征（例如每个类别的一个特征向量）的相对稀缺性，这不足以说明目标域实例中的广泛变化。在本文中，我们提出了一个新颖的学习框架，学习依赖于数据的特征变换，用于评估任意一对源和目标数据实例之间的相似性，以说明目标域的广泛变化。我们提出的方法是基于对参数化的局部特征位移族进行优化，使得源 - 目标自适应相似度函数最大化。因此，我们提出使用潜在结构SVMs来形成零点学习（ZSL），以从训练数据中学习我们的相似性函数。作为示例，我们在所提出的框架下设计特定算法，涉及双线性相似函数和规则化最小二乘法作为特征位移的惩罚。我们在ZSR的几个基准数据集上测试了我们的方法，并且比最先进的方法显示出显着的改进。例如，在一个P＆Y数据集中，我们在识别精度方面可以达到80.89％，比现有技术水平高出11.15％。

##### URL
[https://arxiv.org/abs/1611.07593](https://arxiv.org/abs/1611.07593)

##### PDF
[https://arxiv.org/pdf/1611.07593](https://arxiv.org/pdf/1611.07593)

