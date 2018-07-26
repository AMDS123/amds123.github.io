---
layout: post
title: "Saliency Benchmarking Made Easy: Separating Models, Maps and Metrics"
date: 2018-07-25 13:31:14
categories: arXiv_CV
tags: arXiv_CV Salient Prediction
author: Matthias K&#xfc;mmerer, Thomas S. A. Wallis, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
Dozens of new models on fixation prediction are published every year and compared on open benchmarks such as MIT300 and LSUN. However, progress in the field can be difficult to judge because models are compared using a variety of inconsistent metrics. Here we show that no single saliency map can perform well under all metrics. Instead, we propose a principled approach to solve the benchmarking problem by separating the notions of saliency models, maps and metrics. Inspired by Bayesian decision theory, we define a saliency model to be a probabilistic model of fixation density prediction and a saliency map to be a metric-specific prediction derived from the model density which maximizes the expected performance on that metric given the model density. We derive these optimal saliency maps for the most commonly used saliency metrics (AUC, sAUC, NSS, CC, SIM, KL-Div) and show that they can be computed analytically or approximated with high precision. We show that this leads to consistent rankings in all metrics and avoids the penalties of using one saliency map for all metrics. Our method allows researchers to have their model compete on many different metrics with state-of-the-art in those metrics: "good" models will perform well in all metrics.

##### Abstract (translated by Google)
每年都会发布数十种新的固定预测模型，并在MIT300和LSUN等开放基准上进行比较。然而，由于使用各种不一致的度量来比较模型，因此难以判断该领域的进展。在这里，我们表明没有一个显着性图可以在所有指标下表现良好。相反，我们提出了一种原则性方法，通过分离显着性模型，地图和指标的概念来解决基准问题。受贝叶斯决策理论的启发，我们将显着性模型定义为固定密度预测的概率模型，将显着性图定义为从模型密度导出的度量特定预测，该模型密度在给定模型密度的情况下最大化该度量的预期性能。我们为最常用的显着性度量（AUC，sAUC，NSS，CC，SIM，KL-Div）推导出这些最佳显着性图，并显示它们可以通过分析计算或高精度近似计算。我们证明这导致所有指标的排名一致，并避免了对所有指标使用一个显着性映射的惩罚。我们的方法允许研究人员让他们的模型在许多不同的指标上与这些指标中的最新技术竞争：“好”模型在所有指标中都表现良好。

##### URL
[http://arxiv.org/abs/1704.08615](http://arxiv.org/abs/1704.08615)

##### PDF
[http://arxiv.org/pdf/1704.08615](http://arxiv.org/pdf/1704.08615)

