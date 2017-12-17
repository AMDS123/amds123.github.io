---
layout: post
title: "Influential Sample Selection: A Graph Signal Processing Approach"
date: 2017-11-15 04:52:38
categories: arXiv_CV
tags: arXiv_CV Face Classification
author: Rushil Anirudh, Jayaraman J. Thiagarajan, Rahul Sridhar, Timo Bremer
mathjax: true
---

* content
{:toc}

##### Abstract
With the growing complexity of machine learning techniques, understanding the functioning of black-box models is more important than ever. A recently popular strategy towards interpretability is to generate explanations based on examples -- called influential samples -- that have the largest influence on the model's observed behavior. However, for such an analysis, we are confronted with a plethora of influence metrics. While each of these metrics provide varying levels of representativeness and diversity, existing approaches implicitly couple the definition of influence to their sample selection algorithm, thereby making it challenging to generalize to specific analysis needs. In this paper, we propose a generic approach to influential sample selection, which analyzes the influence metric as a function on a graph constructed using the samples. We show that samples which are critical to recovering the high-frequency content of the function correspond to the most influential samples. Our approach decouples the influence metric from the actual sample selection technique, and hence can be used with any type of task-specific influence. Using experiments in prototype selection, and semi-supervised classification, we show that, even with popularly used influence metrics, our approach can produce superior results in comparison to state-of-the-art approaches. Furthermore, we demonstrate how a novel influence metric can be used to recover the influence structure in characterizing the decision surface, and recovering corrupted labels efficiently.

##### Abstract (translated by Google)
随着机器学习技术的日益复杂，理解黑盒模型的功能比以往更加重要。最近流行的可解释性策略是根据对模型观察到的行为影响最大的例子（称为有影响力的样本）产生解释。但是，对于这样的分析，我们面临着大量的影响力指标。虽然这些指标中的每一个都提供了不同程度的代表性和多样性，但是现有方法将影响的定义隐含地耦合到其样本选择算法，从而使得推广到具体的分析需求具有挑战性。在本文中，我们提出了一个通用的方法来影响样本选择，它将影响度量作为一个函数在一个使用样本构建的图上进行分析。我们表明，对于恢复函数的高频内容至关重要的样本对应于最有影响力的样本。我们的方法将影响度量与实际样本选择技术分离，因此可以用于任何类型的任务特定影响。使用原型选择和半监督分类的实验，我们表明，即使使用常用的影响力指标，与最先进的方法相比，我们的方法可以产生更好的结果。此外，我们还演示了如何使用新的影响度量来恢复表征决策表面的影响结构，并有效地恢复损坏的标签。

##### URL
[https://arxiv.org/abs/1711.05407](https://arxiv.org/abs/1711.05407)

##### PDF
[https://arxiv.org/pdf/1711.05407](https://arxiv.org/pdf/1711.05407)

