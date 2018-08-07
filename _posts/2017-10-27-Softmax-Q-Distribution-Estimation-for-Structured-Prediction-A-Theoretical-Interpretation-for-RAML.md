---
layout: post
title: "Softmax Q-Distribution Estimation for Structured Prediction: A Theoretical Interpretation for RAML"
date: 2017-10-27 19:50:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Classification Prediction Relation Recognition
author: Xuezhe Ma, Pengcheng Yin, Jingzhou Liu, Graham Neubig, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
Reward augmented maximum likelihood (RAML), a simple and effective learning framework to directly optimize towards the reward function in structured prediction tasks, has led to a number of impressive empirical successes. RAML incorporates task-specific reward by performing maximum-likelihood updates on candidate outputs sampled according to an exponentiated payoff distribution, which gives higher probabilities to candidates that are close to the reference output. While RAML is notable for its simplicity, efficiency, and its impressive empirical successes, the theoretical properties of RAML, especially the behavior of the exponentiated payoff distribution, has not been examined thoroughly. In this work, we introduce softmax Q-distribution estimation, a novel theoretical interpretation of RAML, which reveals the relation between RAML and Bayesian decision theory. The softmax Q-distribution can be regarded as a smooth approximation of the Bayes decision boundary, and the Bayes decision rule is achieved by decoding with this Q-distribution. We further show that RAML is equivalent to approximately estimating the softmax Q-distribution, with the temperature $\tau$ controlling approximation error. We perform two experiments, one on synthetic data of multi-class classification and one on real data of image captioning, to demonstrate the relationship between RAML and the proposed softmax Q-distribution estimation method, verifying our theoretical analysis. Additional experiments on three structured prediction tasks with rewards defined on sequential (named entity recognition), tree-based (dependency parsing) and irregular (machine translation) structures show notable improvements over maximum likelihood baselines.

##### Abstract (translated by Google)
奖励增加最大似然（RAML），一个简单有效的学习框架，直接优化结构化预测任务中的奖励功能，已经带来了许多令人印象深刻的实证成功。 RAML通过对根据指数支付分布采样的候选输出执行最大似然更新来结合任务特定的奖励，这给予接近参考输出的候选者更高的概率。虽然RAML以其简单，高效和令人印象深刻的经验成功而着称，但RAML的理论属性，尤其是指数收益分布的行为，尚未得到彻底检验。在这项工作中，我们引入了softmax Q分布估计，这是对RAML的一种新颖的理论解释，揭示了RAML与贝叶斯决策理论之间的关系。 softmax Q分布可以被视为贝叶斯决策边界的平滑近似，并且贝叶斯决策规则通过利用该Q分布进行解码来实现。我们进一步表明，RAML相当于近似估计softmax Q分布，温度$ \ tau $控制近似误差。我们进行了两个实验，一个是关于多类分类的合成数据，另一个是关于图像字幕的实际数据，以演示RAML与提出的softmax Q分布估计方法之间的关系，验证我们的理论分析。对三个结构化预测任务的附加实验，其中在顺序（命名实体识别），基于树的（依赖性解析）和不规则（机器翻译）结构上定义的奖励显示出对最大似然基线的显着改进。

##### URL
[https://arxiv.org/abs/1705.07136](https://arxiv.org/abs/1705.07136)

##### PDF
[https://arxiv.org/pdf/1705.07136](https://arxiv.org/pdf/1705.07136)

