---
layout: post
title: "A Probabilistic Disease Progression Model for Predicting Future Clinical Outcome"
date: 2018-03-13 19:05:08
categories: arXiv_CV
tags: arXiv_CV Inference Prediction
author: Yingying Zhu, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we consider the problem of predicting the course of a progressive disease, such as cancer or Alzheimer's. Progressive diseases often start with mild symptoms that might precede a diagnosis, and each patient follows their own trajectory. Patient trajectories exhibit wild variability, which can be associated with many factors such as genotype, age, or sex. An additional layer of complexity is that, in real life, the amount and type of data available for each patient can differ significantly. For example, for one patient we might have no prior history, whereas for another patient we might have detailed clinical assessments obtained at multiple prior time-points. This paper presents a probabilistic model that can handle multiple modalities (including images and clinical assessments) and variable patient histories with irregular timings and missing entries, to predict clinical scores at future time-points. We use a sigmoidal function to model latent disease progression, which gives rise to clinical observations in our generative model. We implemented an approximate Bayesian inference strategy on the proposed model to estimate the parameters on data from a large population of subjects. Furthermore, the Bayesian framework enables the model to automatically fine-tune its predictions based on historical observations that might be available on the test subject. We applied our method to a longitudinal Alzheimer's disease dataset with more than 3000 subjects [23] and present a detailed empirical analysis of prediction performance under different scenarios, with comparisons against several benchmarks. We also demonstrate how the proposed model can be interrogated to glean insights about temporal dynamics in Alzheimer's disease.

##### Abstract (translated by Google)
在这项工作中，我们考虑预测疾病进展的问题，如癌症或阿尔茨海默病。进行性疾病通常以可能在诊断之前的轻度症状开始，并且每位患者都遵循自己的运动轨迹。患者的轨迹表现出野生变异性，这可能与许多因素有关，如基因型，年龄或性别。另外一层复杂性是，在现实生活中，每个病人可用的数据量和类型可能会有很大差异。例如，对于一名患者，我们可能没有先前的病史，而对于另一名患者，我们可能在多个先前的时间点获得详细的临床评估。本文提出了一种概率模型，可以处理多种形式（包括图像和临床评估）以及具有不规则时间和缺失条目的可变患者病史，以预测未来时间点的临床评分。我们使用S形函数来模拟潜在的疾病进展，这引起了我们的生成模型中的临床观察。我们对所提出的模型实施了近似贝叶斯推理策略，以估计来自大量受试者数据的参数。此外，贝叶斯框架使模型能够基于测试主题上可能提供的历史观察值自动微调其预测。我们将该方法应用于纵向阿尔茨海默病数据集，其中包含3000多名受试者[23]，并对不同情况下的预测性能进行了详细的实证分析，并与几个基准进行比较。我们还展示了该模型如何被审问以收集关于阿尔茨海默病时间动态的见解。

##### URL
[https://arxiv.org/abs/1803.05011](https://arxiv.org/abs/1803.05011)

##### PDF
[https://arxiv.org/pdf/1803.05011](https://arxiv.org/pdf/1803.05011)

