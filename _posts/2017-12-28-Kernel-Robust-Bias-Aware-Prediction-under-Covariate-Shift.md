---
layout: post
title: "Kernel Robust Bias-Aware Prediction under Covariate Shift"
date: 2017-12-28 20:23:18
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Anqi Liu, Rizal Fathony, Brian D. Ziebart
mathjax: true
---

* content
{:toc}

##### Abstract
Under covariate shift, training (source) data and testing (target) data differ in input space distribution, but share the same conditional label distribution. This poses a challenging machine learning task. Robust Bias-Aware (RBA) prediction provides the conditional label distribution that is robust to the worstcase logarithmic loss for the target distribution while matching feature expectation constraints from the source distribution. However, employing RBA with insufficient feature constraints may result in high certainty predictions for much of the source data, while leaving too much uncertainty for target data predictions. To overcome this issue, we extend the representer theorem to the RBA setting, enabling minimization of regularized expected target risk by a reweighted kernel expectation under the source distribution. By applying kernel methods, we establish consistency guarantees and demonstrate better performance of the RBA classifier than competing methods on synthetically biased UCI datasets as well as datasets that have natural covariate shift.

##### Abstract (translated by Google)
在协变量下，训练（源）数据和测试（目标）数据在输入空间分布上不同，但共享相同的条件标签分布。这提出了具有挑战性的机器学习任务。稳健的偏置感知（RBA）预测提供了对于目标分布的最差对数损失是鲁棒的条件标签分布，同时匹配来自源分布的特征期望约束。然而，采用不充分的特征约束的RBA可能导致大部分源数据的高确定性预测，同时为目标数据预测留下太多的不确定性。为了克服这个问题，我们将代表定理扩展到RBA设置，通过源分布下的重新加权核心期望使正则化的预期目标风险最小化。通过应用核方法，我们建立了一致性保证，并证明RBA分类器的性能优于竞争对合成偏向UCI数据集的方法以及具有自然协变量的数据集。

##### URL
[https://arxiv.org/abs/1712.10050](https://arxiv.org/abs/1712.10050)

##### PDF
[https://arxiv.org/pdf/1712.10050](https://arxiv.org/pdf/1712.10050)

