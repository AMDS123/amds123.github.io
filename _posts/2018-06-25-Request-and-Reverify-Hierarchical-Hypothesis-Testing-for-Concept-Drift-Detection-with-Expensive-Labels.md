---
layout: post
title: "Request-and-Reverify: Hierarchical Hypothesis Testing for Concept Drift Detection with Expensive Labels"
date: 2018-06-25 22:15:19
categories: arXiv_AI
tags: arXiv_AI Object_Detection Classification Detection
author: Shujian Yu, Xiaoyang Wang, Jose C. Principe
mathjax: true
---

* content
{:toc}

##### Abstract
One important assumption underlying common classification models is the stationarity of the data. However, in real-world streaming applications, the data concept indicated by the joint distribution of feature and label is not stationary but drifting over time. Concept drift detection aims to detect such drifts and adapt the model so as to mitigate any deterioration in the model's predictive performance. Unfortunately, most existing concept drift detection methods rely on a strong and over-optimistic condition that the true labels are available immediately for all already classified instances. In this paper, a novel Hierarchical Hypothesis Testing framework with Request-and-Reverify strategy is developed to detect concept drifts by requesting labels only when necessary. Two methods, namely Hierarchical Hypothesis Testing with Classification Uncertainty (HHT-CU) and Hierarchical Hypothesis Testing with Attribute-wise "Goodness-of-fit" (HHT-AG), are proposed respectively under the novel framework. In experiments with benchmark datasets, our methods demonstrate overwhelming advantages over state-of-the-art unsupervised drift detectors. More importantly, our methods even outperform DDM (the widely used supervised drift detector) when we use significantly fewer labels.

##### Abstract (translated by Google)
共同分类模型的一个重要假设是数据的平稳性。然而，在现实世界的流媒体应用中，由特征和标签的联合分布所表示的数据概念并不是固定的，而是随着时间的推移而漂移。概念漂移检测旨在检测这种漂移并调整模型，以减轻模型预测性能的任何恶化。不幸的是，大多数现有的概念漂移检测方法依赖于一个强大而过分乐观的条件，即所有已分类的实例都可以立即使用真正的标签。在本文中，开发了一种新的基于请求和重新验证策略的分层假设测试框架，通过仅在必要时请求标签来检测概念漂移。在新框架下分别提出了两种方法，即分类不确定性分层假设检验（HHT-CU）和基于属性的“合适吻合度分级检验”（HHT-AG）。在基准数据集的实验中，我们的方法比最先进的无监督漂移探测器显示出绝对的优势。更重要的是，当我们使用明显较少的标签时，我们的方法甚至胜过DDM（广泛使用的监督式漂移检测器）。

##### URL
[http://arxiv.org/abs/1806.10131](http://arxiv.org/abs/1806.10131)

##### PDF
[http://arxiv.org/pdf/1806.10131](http://arxiv.org/pdf/1806.10131)

