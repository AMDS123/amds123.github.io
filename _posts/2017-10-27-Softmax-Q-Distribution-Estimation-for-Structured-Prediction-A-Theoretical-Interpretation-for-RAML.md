---
layout: post
title: "Softmax Q-Distribution Estimation for Structured Prediction: A Theoretical Interpretation for RAML"
date: 2017-10-27 19:50:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Recognition
author: Xuezhe Ma, Pengcheng Yin, Jingzhou Liu, Graham Neubig, Eduard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
Reward augmented maximum likelihood (RAML), a simple and effective learning framework to directly optimize towards the reward function in structured prediction tasks, has led to a number of impressive empirical successes. RAML incorporates task-specific reward by performing maximum-likelihood updates on candidate outputs sampled according to an exponentiated payoff distribution, which gives higher probabilities to candidates that are close to the reference output. While RAML is notable for its simplicity, efficiency, and its impressive empirical successes, the theoretical properties of RAML, especially the behavior of the exponentiated payoff distribution, has not been examined thoroughly. In this work, we introduce softmax Q-distribution estimation, a novel theoretical interpretation of RAML, which reveals the relation between RAML and Bayesian decision theory. The softmax Q-distribution can be regarded as a smooth approximation of the Bayes decision boundary, and the Bayes decision rule is achieved by decoding with this Q-distribution. We further show that RAML is equivalent to approximately estimating the softmax Q-distribution, with the temperature $\tau$ controlling approximation error. We perform two experiments, one on synthetic data of multi-class classification and one on real data of image captioning, to demonstrate the relationship between RAML and the proposed softmax Q-distribution estimation method, verifying our theoretical analysis. Additional experiments on three structured prediction tasks with rewards defined on sequential (named entity recognition), tree-based (dependency parsing) and irregular (machine translation) structures show notable improvements over maximum likelihood baselines.

##### Abstract (translated by Google)
奖励增加最大可能性（RAML）是一种简单而有效的学习框架，直接针对结构化预测任务中的奖励功能进行优化，从而获得了许多令人印象深刻的经验成功。 RAML通过对根据指数收益分布采样的候选输出执行最大似然更新来合并任务特定奖励，这给接近参考输出的候选提供更高的概率。虽然RAML以其简单性，高效性以及令人印象深刻的经验成功而着称，但RAML的理论特性，特别是指数化收益分布的行为，还没有得到彻底的检验。在这项工作中，我们引入softmax Q分布估计，这是对RAML的一种新颖的理论解释，揭示了RAML和贝叶斯决策理论之间的关系。 softmax Q分布可以看成是贝叶斯决策边界的一个平滑近似，贝叶斯决策规则是通过用这个Q分布进行解码来实现的。我们进一步表明，RAML相当于近似估计softmax Q分布，温度为$ \ t $ $控制近似误差。我们进行了两个实验，一个是关于多类分类的综合数据，另一个是关于图像字幕的实际数据，以展示RAML和所提出的softmax Q分布估计方法之间的关系，验证了我们的理论分析。在连续（命名实体识别），基于树（依赖性分析）和不规则（机器翻译）结构上定义奖励的三个结构化预测任务上的额外实验显示了对最大可能性基线的显着改进。

##### URL
[https://arxiv.org/abs/1705.07136](https://arxiv.org/abs/1705.07136)

