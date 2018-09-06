---
layout: post
title: "t-Exponential Memory Networks for Question-Answering Machines"
date: 2018-09-04 20:09:01
categories: arXiv_CL
tags: arXiv_CL Sparse Attention Inference Deep_Learning Language_Model Prediction Memory_Networks
author: Kyriakos Tolias, Sotirios Chatzis
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning have brought to the fore models that can make multiple computational steps in the service of completing a task; these are capable of describ- ing long-term dependencies in sequential data. Novel recurrent attention models over possibly large external memory modules constitute the core mechanisms that enable these capabilities. Our work addresses learning subtler and more complex underlying temporal dynamics in language modeling tasks that deal with sparse sequential data. To this end, we improve upon these recent advances, by adopting concepts from the field of Bayesian statistics, namely variational inference. Our proposed approach consists in treating the network parameters as latent variables with a prior distribution imposed over them. Our statistical assumptions go beyond the standard practice of postulating Gaussian priors. Indeed, to allow for handling outliers, which are prevalent in long observed sequences of multivariate data, multivariate t-exponential distributions are imposed. On this basis, we proceed to infer corresponding posteriors; these can be used for inference and prediction at test time, in a way that accounts for the uncertainty in the available sparse training data. Specifically, to allow for our approach to best exploit the merits of the t-exponential family, our method considers a new t-divergence measure, which generalizes the concept of the Kullback-Leibler divergence. We perform an extensive experimental evaluation of our approach, using challenging language modeling benchmarks, and illustrate its superiority over existing state-of-the-art techniques.

##### Abstract (translated by Google)
深度学习的最新进展已经带来了可以在完成任务的过程中进行多个计算步骤的模型。这些能够描述顺序数据中的长期依赖性。可能大的外部存储器模块上的新型周期性注意模型构成了实现这些能力的核心机制。我们的工作涉及处理稀疏顺序数据的语言建模任务中的学习更微妙和更复杂的基础时间动态。为此，我们通过采用贝叶斯统计学领域的概念，即变分推理，改进了这些最新进展。我们提出的方法在于将网络参数视为潜在变量，并对其施加先验分布。我们的统计假设超出了假设高斯先验的标准做法。实际上，为了允许处理在长期观察的多变量数据序列中普遍存在的异常值，施加多变量t指数分布。在此基础上，我们继续推断相应的后验;这些可以用于在测试时进行推理和预测，其方式考虑了可用稀疏训练数据中的不确定性。具体来说，为了使我们的方法能够最好地利用t指数族的优点，我们的方法考虑了一种新的t-散度测量，它概括了Kullback-Leibler散度的概念。我们使用具有挑战性的语言建模基准对我们的方法进行了广泛的实验评估，并说明了其优于现有最先进技术的优势。

##### URL
[http://arxiv.org/abs/1809.01229](http://arxiv.org/abs/1809.01229)

##### PDF
[http://arxiv.org/pdf/1809.01229](http://arxiv.org/pdf/1809.01229)

