---
layout: post
title: "Learning Representations of Ultrahigh-dimensional Data for Random Distance-based Outlier Detection"
date: 2018-06-13 00:53:56
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge Represenation_Learning Detection
author: Guansong Pang, Longbing Cao, Ling Chen, Huan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning expressive low-dimensional representations of ultrahigh-dimensional data, e.g., data with thousands/millions of features, has been a major way to enable learning methods to address the curse of dimensionality. However, existing unsupervised representation learning methods mainly focus on preserving the data regularity information and learning the representations independently of subsequent outlier detection methods, which can result in suboptimal and unstable performance of detecting irregularities (i.e., outliers). 
 This paper introduces a ranking model-based framework, called RAMODO, to address this issue. RAMODO unifies representation learning and outlier detection to learn low-dimensional representations that are tailored for a state-of-the-art outlier detection approach - the random distance-based approach. This customized learning yields more optimal and stable representations for the targeted outlier detectors. Additionally, RAMODO can leverage little labeled data as prior knowledge to learn more expressive and application-relevant representations. We instantiate RAMODO to an efficient method called REPEN to demonstrate the performance of RAMODO. 
 Extensive empirical results on eight real-world ultrahigh dimensional data sets show that REPEN (i) enables a random distance-based detector to obtain significantly better AUC performance and two orders of magnitude speedup; (ii) performs substantially better and more stably than four state-of-the-art representation learning methods; and (iii) leverages less than 1% labeled data to achieve up to 32% AUC improvement.

##### Abstract (translated by Google)
学习超高维数据的表达低维表示，例如具有数千/数百万特征的数据，一直是使学习方法能够解决维数灾难的主要方式。然而，现有的无监督表示学习方法主要集中于保存数据规律性信息和独立于随后的异常值检测方法学习表示，这可能导致检测不规则性（即异常值）的次优和不稳定性能。
 本文介绍了一个名为RAMODO的基于排名模型的框架来解决这个问题。 RAMODO统一了表示学习和异常值检测，以学习针对最先进的异常值检测方法（基于随机距离的方法）量身定制的低维表示。这种定制的学习为目标离群值检测器提供更优化和稳定的表示。此外，RAMODO可以利用很少的标签数据作为先前的知识来学习更多表达性和与应用相关的表示。我们将RAMODO实例化为一种称为REPEN的有效方法来演示RAMODO的性能。
 对八个真实世界超高维数据集的广泛实证结果表明，REPEN（i）使基于随机距离的检测器能够获得显着更好的AUC性能和两个数量级的加速; （ii）比四种最先进的表示学习方法表现得更好更稳定;和（iii）利用少于1％的标签数据来实现高达32％的AUC改善。

##### URL
[http://arxiv.org/abs/1806.04808](http://arxiv.org/abs/1806.04808)

##### PDF
[http://arxiv.org/pdf/1806.04808](http://arxiv.org/pdf/1806.04808)

