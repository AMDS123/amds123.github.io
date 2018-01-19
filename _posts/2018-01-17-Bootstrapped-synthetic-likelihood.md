---
layout: post
title: "Bootstrapped synthetic likelihood"
date: 2018-01-17 23:16:04
categories: arXiv_AI
tags: arXiv_AI Inference
author: Richard G. Everitt
mathjax: true
---

* content
{:toc}

##### Abstract
Approximate Bayesian computation (ABC) and synthetic likelihood (SL) techniques have enabled the use of Bayesian inference for models that may be simulated, but for which the likelihood cannot be evaluated pointwise at values of an unknown parameter $\theta$. The main idea in ABC and SL is to, for different values of $\theta$ (usually chosen using a Monte Carlo algorithm), build estimates of the likelihood based on simulations from the model conditional on $\theta$. The quality of these estimates determines the efficiency of an ABC/SL algorithm. In standard ABC/SL, the only means to improve an estimated likelihood at $\theta$ is to simulate more times from the model conditional on $\theta$, which is infeasible in cases where the simulator is computationally expensive. In this paper we describe how to use bootstrapping as a means for improving SL estimates whilst using fewer simulations from the model, and also investigate its use in ABC. Further, we investigate the use of the bag of little bootstraps as a means for applying this approach to large datasets, yielding Monte Carlo algorithms that accurately approximate posterior distributions whilst only simulating subsamples of the full data. Examples of the approach applied to i.i.d., temporal and spatial data are given.

##### Abstract (translated by Google)
近似贝叶斯计算（ABC）和合成似然（SL）技术使得能够对可能被模拟的模型使用贝叶斯推断，但是对于未知参数$ \ theta $的值而言，似然性不能被逐点评估。 ABC和SL中的主要思想是，对于不同的$ \ theta $值（通常使用蒙特卡洛算法进行选择），基于来自$ \ theta $的模型的模拟来建立可能性的估计值。这些估计的质量决定了ABC / SL算法的效率。在标准的ABC / SL中，改善$ \θ的估计可能性的唯一方法是从$ \ theta $模拟更多的时间，在模拟器计算成本昂贵的情况下这是不可行的。在本文中，我们描述了如何使用引导作为改善SL估计的手段，同时使用模型中较少的模拟，并研究它在ABC中的使用。此外，我们研究了小引导包的使用作为将这种方法应用于大型数据集的手段，得到的Monte Carlo算法精确地近似后验分布，而只模拟完整数据的子样本。给出了应用于i.i.d.，时间和空间数据的方法的例子。

##### URL
[http://arxiv.org/abs/1711.05825](http://arxiv.org/abs/1711.05825)

##### PDF
[http://arxiv.org/pdf/1711.05825](http://arxiv.org/pdf/1711.05825)

