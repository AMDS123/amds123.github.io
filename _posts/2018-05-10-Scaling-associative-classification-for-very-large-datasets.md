---
layout: post
title: "Scaling associative classification for very large datasets"
date: 2018-05-10 08:41:55
categories: arXiv_AI
tags: arXiv_AI Classification Prediction
author: Luca Venturini, Elena Baralis, Paolo Garza
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning algorithms are nowadays successfully scaling up to datasets that are very large in volume, leveraging the potential of in-memory cluster-computing Big Data frameworks. Still, massive datasets with a number of large-domain categorical features are a difficult challenge for any classifier. Most off-the-shelf solutions cannot cope with this problem. In this work we introduce DAC, a Distributed Associative Classifier. DAC exploits ensemble learning to distribute the training of an associative classifier among parallel workers and improve the final quality of the model. Furthermore, it adopts several novel techniques to reach high scalability without sacrificing quality, among which a preventive pruning of classification rules in the extraction phase based on Gini impurity. We ran experiments on Apache Spark, on a real large-scale dataset with more than 4 billion records and 800 million distinct categories. The results showed that DAC improves on a state-of-the-art solution in both prediction quality and execution time. Since the generated model is human-readable, it can not only classify new records, but also allow understanding both the logic behind the prediction and the properties of the model, becoming a useful aid for decision makers.

##### Abstract (translated by Google)
目前，监督式学习算法已成功扩展到数量庞大的数据集，充分利用了内存中集群计算大数据框架的潜力。尽管如此，对于任何分类器而言，具有许多大范围分类特征的海量数据集都是一项艰巨的挑战。大多数现成的解决方案都无法解决这个问题。在这项工作中，我们介绍分布式关联分类器DAC。 DAC利用集成学习在并行工作人员中分发关联分类器的训练，并提高模型的最终质量。此外，它采用了几种新技术，在不牺牲质量的前提下实现高扩展性，其中基于基尼杂质的提取阶段中的分类规则的预防性修剪。我们在Apache Spark上实验了一个真实的大型数据集，其中有超过40亿条记录和8亿个不同的类别。结果显示，DAC在预测质量和执行时间方面都有先进的解决方案。由于生成的模型是人类可读的，因此它不仅可以对新记录进行分类，还可以理解预测背后的逻辑和模型的属性，从而成为决策者的有用帮助。

##### URL
[http://arxiv.org/abs/1805.03887](http://arxiv.org/abs/1805.03887)

##### PDF
[http://arxiv.org/pdf/1805.03887](http://arxiv.org/pdf/1805.03887)

