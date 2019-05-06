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


##### URL
[https://arxiv.org/abs/1705.07136](https://arxiv.org/abs/1705.07136)

##### PDF
[https://arxiv.org/pdf/1705.07136](https://arxiv.org/pdf/1705.07136)

