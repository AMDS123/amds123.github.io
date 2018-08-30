---
layout: post
title: "Zero-shot Transfer Learning for Semantic Parsing"
date: 2018-08-27 16:12:36
categories: arXiv_CL
tags: arXiv_CL Adversarial Transfer_Learning Classification Prediction
author: Javid Dadashkarimi, Alexander Fabbri, Sekhar Tatikonda, Dragomir R. Radev
mathjax: true
---

* content
{:toc}

##### Abstract
While neural networks have shown impressive performance on large datasets, applying these models to tasks where little data is available remains a challenging problem. 
 In this paper we propose to use feature transfer in a zero-shot experimental setting on the task of semantic parsing. 
 We first introduce a new method for learning the shared space between multiple domains based on the prediction of the domain label for each example. 
 Our experiments support the superiority of this method in a zero-shot experimental setting in terms of accuracy metrics compared to state-of-the-art techniques. 
 In the second part of this paper we study the impact of individual domains and examples on semantic parsing performance. 
 We use influence functions to this aim and investigate the sensitivity of domain-label classification loss on each example. 
 Our findings reveal that cross-domain adversarial attacks identify useful examples for training even from the domains the least similar to the target domain. Augmenting our training data with these influential examples further boosts our accuracy at both the token and the sequence level.

##### Abstract (translated by Google)
虽然神经网络在大型数据集上表现出了令人印象深刻的性能，但将这些模型应用于数据很少的任务仍然是一个具有挑战性
 在本文中，我们建议在零搜索实验环境中使用特征转移来完成语义分析的任务。
 我们首先介绍一种基于每个示例的域标签预测来学习多个域之间的共享空间的新方法。
 与最先进的技术相比，我们的实验在精确度指标方面支持这种方法在零射击实验设置中的优越性。
 在本文的第二部分，我们研究了各个域和示例对语义解析性能的影响。
 我们使用影响函数来实现这一目标，并研究每个例子中域标签分类丢失的敏感性。
 我们的研究结果表明，跨域对抗性攻击确定了即使从与目标域最不相似的域进行培训的有用示例。使用这些有影响力的示例扩充我们的训练数据进一步提高了我们在令牌和序列级别的准确性。

##### URL
[http://arxiv.org/abs/1808.09889](http://arxiv.org/abs/1808.09889)

##### PDF
[http://arxiv.org/pdf/1808.09889](http://arxiv.org/pdf/1808.09889)

