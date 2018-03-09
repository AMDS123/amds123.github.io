---
layout: post
title: "Applicability and interpretation of the deterministic weighted cepstral distance"
date: 2018-03-08 14:31:46
categories: arXiv_CV
tags: arXiv_CV
author: Oliver Lauwers, Bart De Moor
mathjax: true
---

* content
{:toc}

##### Abstract
Quantifying similarity between data objects is an important part of modern data science. Deciding what similarity measure to use is very application dependent. In this paper, we combine insights from systems theory and machine learning, and investigate the weighted cepstral distance, which was previously defined for signals coming from ARMA models. We provide an extension of this distance to invertible deterministic linear time invariant single input single output models, and assess its applicability. We show that it can always be interpreted in terms of the poles and zeros of the underlying model, and that, in the case of stable, minimum-phase, or unstable, maximum-phase models, a geometrical interpretation in terms of subspace angles can be given. We then devise a method to assess stability and phase-type of the generating models, using only input/output signal information. In this way, we prove a connection between the extended weighted cepstral distance and a weighted cepstral model norm. In this way, we provide a purely data-driven way to assess different underlying dynamics of input/output signal pairs, without the need for any system identification step. This can be useful in machine learning tasks such as time series clustering. An iPython tutorial is published complementary to this paper, containing implementations of the various methods and algorithms presented here, as well as some numerical illustrations of the equivalences proven here.

##### Abstract (translated by Google)
量化数据对象之间的相似性是现代数据科学的重要组成部分。决定使用什么相似性度量是非常依赖于应用程序的。在本文中，我们结合了系统理论和机器学习的见解，并研究了先前为来自ARMA模型的信号定义的加权倒谱距离。我们将这个距离延伸到可逆确定性线性时不变单输入单输出模型，并评估其适用性。我们表明，它总是可以根据基础模型的极点和零点来解释，并且在稳定，最小相位或不稳定的最大相位模型的情况下，根据子空间角度的几何解释可以被给予。然后，我们设计一种方法来评估生成模型的稳定性和相位类型，仅使用输入/输出信号信息。这样，我们证明了扩展加权倒谱距离与加权倒谱模型范数之间的关系。这样，我们提供纯粹的数据驱动方式来评估输入/输出信号对的不同底层动态，而不需要任何系统识别步骤。这对于时间序列聚类等机器学习任务非常有用。 iPython教程与本文相辅相成，包含了这里介绍的各种方法和算法的实现，以及一些在这里证明的等价性的数字插图。

##### URL
[http://arxiv.org/abs/1803.03104](http://arxiv.org/abs/1803.03104)

##### PDF
[http://arxiv.org/pdf/1803.03104](http://arxiv.org/pdf/1803.03104)

