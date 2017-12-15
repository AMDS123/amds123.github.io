---
layout: post
title: "Discriminative Bayesian Dictionary Learning for Classification"
date: 2015-03-27 08:36:15
categories: arXiv_CV
tags: arXiv_CV Sparse Face Action_Recognition Inference Classification Recognition
author: Naveed Akhtar, Faisal Shafait, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Bayesian approach to learn discriminative dictionaries for sparse representation of data. The proposed approach infers probability distributions over the atoms of a discriminative dictionary using a Beta Process. It also computes sets of Bernoulli distributions that associate class labels to the learned dictionary atoms. This association signifies the selection probabilities of the dictionary atoms in the expansion of class-specific data. Furthermore, the non-parametric character of the proposed approach allows it to infer the correct size of the dictionary. We exploit the aforementioned Bernoulli distributions in separately learning a linear classifier. The classifier uses the same hierarchical Bayesian model as the dictionary, which we present along the analytical inference solution for Gibbs sampling. For classification, a test instance is first sparsely encoded over the learned dictionary and the codes are fed to the classifier. We performed experiments for face and action recognition; and object and scene-category classification using five public datasets and compared the results with state-of-the-art discriminative sparse representation approaches. Experiments show that the proposed Bayesian approach consistently outperforms the existing approaches.

##### Abstract (translated by Google)
我们提出一种贝叶斯方法来学习用于数据稀疏表示的区分性字典。所提出的方法使用Beta过程来推断可辨字典中原子的概率分布。它还计算将类标签与学习的字典原子相关联的伯努利分布集。这种关联表示在扩展类特定数据时字典原子的选择概率。此外，所提出的方法的非参数特征允许它推断字典的正确大小。我们利用上述伯努利分布分别学习一个线性分类器。分类器使用与字典相同的分层贝叶斯模型，这是我们在分析推理解决方案中提供的吉布斯采样。对于分类，测试实例首先在学习的字典上进行稀疏编码，并将代码馈送给分类器。我们进行了脸部和动作识别的实验。以及使用五个公共数据集的对象和场景类别分类，并将结果与​​最先进的判别性稀疏表示方法进行比较。实验表明，所提出的贝叶斯方法一直胜过现有的方法。

##### URL
[https://arxiv.org/abs/1503.07989](https://arxiv.org/abs/1503.07989)

##### PDF
[https://arxiv.org/pdf/1503.07989](https://arxiv.org/pdf/1503.07989)

