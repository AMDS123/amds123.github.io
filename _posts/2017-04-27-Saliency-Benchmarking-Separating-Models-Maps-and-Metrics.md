---
layout: post
title: "Saliency Benchmarking: Separating Models, Maps and Metrics"
date: 2017-04-27 15:07:42
categories: arXiv_CV
tags: arXiv_CV Salient Prediction
author: Matthias Kümmerer, Thomas S. A. Wallis, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
The field of fixation prediction is heavily model-driven, with dozens of new models published every year. However, progress in the field can be difficult to judge because models are compared using a variety of inconsistent metrics. As soon as a saliency map is optimized for a certain metric, it is penalized by other metrics. Here we propose a principled approach to solve the benchmarking problem: we separate the notions of saliency models and saliency maps. We define a saliency model to be a probabilistic model of fixation density prediction and, inspired by Bayesian decision theory, a saliency map to be a metric-specific prediction derived from the model density which maximizes the expected performance on that metric. We derive the optimal saliency map for the most commonly used saliency metrics (AUC, sAUC, NSS, CC, SIM, KL-Div) and show that they can be computed analytically or approximated with high precision using the model density. We show that this leads to consistent rankings in all metrics and avoids the penalties of using one saliency map for all metrics. Under this framework, "good" models will perform well in all metrics.

##### Abstract (translated by Google)
固视预测领域大量模型驱动，每年发布几十个新模型。然而，由于模型是使用各种不一致的指标进行比较，因此难以判断该领域的进展。一旦显着图针对某个指标进行了优化，就会受到其他指标的影响。在这里我们提出一个有原则的方法来解决基准问题：我们分开显着性模型和显着性图的概念。我们将显着性模型定义为固定密度预测的概率模型，并且受贝叶斯决策理论的启发，将显着性图作为从模型密度导出的特定于度量的预测，其最大化该度量的预期性能。我们推导出最常用的显着性度量（AUC，sAUC，NSS，CC，SIM，KL-Div）的最优显着性图，并显示它们可以使用模型密度进行解析计算或高精度近似计算。我们显示这导致了所有度量标准的一致排名，并避免了对所有度量标准使用一个显着性图的处罚。在这个框架下，“好”模式将在所有指标中表现良好。

##### URL
[https://arxiv.org/abs/1704.08615](https://arxiv.org/abs/1704.08615)

##### PDF
[https://arxiv.org/pdf/1704.08615](https://arxiv.org/pdf/1704.08615)

