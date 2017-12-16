---
layout: post
title: "Efficient Likelihood Bayesian Constrained Local Model"
date: 2016-11-30 00:41:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Optimization Inference Detection
author: Hailiang Li, Kin-Man Lam, Man-Yau Chiu, Kangheng Wu, Zhibin Lei
mathjax: true
---

* content
{:toc}

##### Abstract
The constrained local model (CLM) proposes a paradigm that the locations of a set of local landmark detectors are constrained to lie in a subspace, spanned by a shape point distribution model (PDM). Fitting the model to an object involves two steps. A response map, which represents the likelihood of the location of a landmark, is first computed for each landmark using local-texture detectors. Then, an optimal PDM is determined by jointly maximizing all the response maps simultaneously, with a global shape constraint. This global optimization can be considered as a Bayesian inference problem, where the posterior distribution of the shape parameters, as well as the pose parameters, can be inferred using maximum a posteriori (MAP). In this paper, we present a cascaded face-alignment approach, which employs random-forest regressors to estimate the positions of each landmark, as a likelihood term, efficiently in the CLM model. Interpretation from CLM framework, this algorithm is named as an efficient likelihood Bayesian constrained local model (elBCLM). Furthermore, in each stage of the regressors, the PDM non-rigid parameters of previous stage can work as shape clues for training each stage regressors. Experimental results on benchmarks show our approach achieve about 3 to 5 times speed-up compared with CLM models and improve around 10% on fitting quality compare with the same setting regression models.

##### Abstract (translated by Google)
约束局部模型（CLM）提出了一种范例，即一组局部标志检测器的位置被限制在位于由形状点分布模型（PDM）跨越的子空间中。将模型拟合到一个对象涉及两个步骤。首先使用局部纹理检测器针对每个地标计算表示地标的位置的可能性的响应地图。然后，通过联合最大化所有响应图来确定最优PDM，同时具有全局形状约束。这种全局优化可以被认为是贝叶斯推理问题，其中形状参数的后验分布以及姿态参数可以使用最大后验概率（MAP）来推断。在本文中，我们提出了一个级联的面对齐方法，该方法使用随机森林回归器在CLM模型中有效地估计每个地标的位置，作为似然项。从CLM框架的解释，这个算法被命名为一个高效的似然贝叶斯约束局部模型（elBCLM）。此外，在回归的每个阶段，前一阶段的PDM非刚性参数可以作为训练各阶段回归机的形状线索。基准的实验结果表明，与CLM模型相比，我们的方法实现了约3至5倍的加速，并且与相同设置的回归模型相比，拟合质量提高了约10％。

##### URL
[https://arxiv.org/abs/1611.09956](https://arxiv.org/abs/1611.09956)

##### PDF
[https://arxiv.org/pdf/1611.09956](https://arxiv.org/pdf/1611.09956)

