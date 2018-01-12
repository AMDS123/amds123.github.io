---
layout: post
title: "Evolving Ensemble Fuzzy Classifier"
date: 2017-05-18 08:19:41
categories: arXiv_AI
tags: arXiv_AI Classification Detection
author: Mahardhika Pratama, Witold Pedrycz, Edwin Lughofer
mathjax: true
---

* content
{:toc}

##### Abstract
The concept of ensemble learning offers a promising avenue in learning from data streams under complex environments because it addresses the bias and variance dilemma better than its single model counterpart and features a reconfigurable structure, which is well suited to the given context. While various extensions of ensemble learning for mining non-stationary data streams can be found in the literature, most of them are crafted under a static base classifier and revisits preceding samples in the sliding window for a retraining step. This feature causes computationally prohibitive complexity and is not flexible enough to cope with rapidly changing environments. Their complexities are often demanding because it involves a large collection of offline classifiers due to the absence of structural complexities reduction mechanisms and lack of an online feature selection mechanism. A novel evolving ensemble classifier, namely Parsimonious Ensemble pENsemble, is proposed in this paper. pENsemble differs from existing architectures in the fact that it is built upon an evolving classifier from data streams, termed Parsimonious Classifier pClass. pENsemble is equipped by an ensemble pruning mechanism, which estimates a localized generalization error of a base classifier. A dynamic online feature selection scenario is integrated into the pENsemble. This method allows for dynamic selection and deselection of input features on the fly. pENsemble adopts a dynamic ensemble structure to output a final classification decision where it features a novel drift detection scenario to grow the ensemble structure. The efficacy of the pENsemble has been numerically demonstrated through rigorous numerical studies with dynamic and evolving data streams where it delivers the most encouraging performance in attaining a tradeoff between accuracy and complexity.

##### Abstract (translated by Google)
集成学习的概念为复杂环境下的数据流学习提供了一个有前途的途径，因为它比单一模型更好地解决了偏差和方差两难问题，并具有可重构的结构，非常适合于给定的环境。尽管在文献中可以找到用于挖掘非平稳数据流的集合学习的各种扩展，但是其大部分是在静态基本分类器下制作的，并且在滑动窗口中重新访问前面的样本以进行再训练步骤。这个特性导致计算复杂度不高，并且不够灵活，无法应对快速变化的环境。由于缺乏结构复杂度减少机制和缺少在线特征选择机制，因此涉及到大量的离线分类器，因此其复杂性往往非常高。本文提出了一种新的进化集成分类器，即Parsimonious Ensemble pENsemble。 pENsemble与现有体系结构的不同之处在于它建立在数据流的不断发展的分类器之上，被称为Parsimonious Classifier pClass。 pENsemble由集合修剪机制装备，其估计基本分类器的局部泛化误差。动态的在线特征选择场景被集成到pENsemble中。这种方法允许动态选择和取消动态输入功能。 pENsemble采用动态集成结构来输出最终的分类决策，其中具有新颖的漂移检测场景以生成集合结构。 pENsemble的功效已经通过严格的数值研究，以动态的和不断发展的数据流的数字表现得到了证明，在这个数据流中，它在实现准确性和复杂性之间取得最令人鼓舞的性能。

##### URL
[http://arxiv.org/abs/1705.06460](http://arxiv.org/abs/1705.06460)

##### PDF
[http://arxiv.org/pdf/1705.06460](http://arxiv.org/pdf/1705.06460)

