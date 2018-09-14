---
layout: post
title: "Does Your Model Know the Digit 6 Is Not a Cat? A Less Biased Evaluation of 'Outlier' Detectors"
date: 2018-09-13 01:15:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Deep_Learning Detection
author: Alireza Shafaei, Mark Schmidt, James J. Little
mathjax: true
---

* content
{:toc}

##### Abstract
In the real world, a learning system could receive an input that looks nothing like anything it has seen during training, and this can lead to unpredictable behaviour. We thus need to know whether any given input belongs to the population distribution of the training data to prevent unpredictable behaviour in deployed systems. A recent surge of interest on this problem has led to the development of sophisticated techniques in the deep learning literature. However, due to the absence of a standardized problem formulation or an exhaustive evaluation, it is not evident if we can rely on these methods in practice. What makes this problem different from a typical supervised learning setting is that we cannot model the diversity of out-of-distribution samples in practice. The distribution of outliers used in training may not be the same as the distribution of outliers encountered in the application. Therefore, classical approaches that learn inliers vs. outliers with only two datasets can yield optimistic results. We introduce OD-test, a three-dataset evaluation scheme as a practical and more reliable strategy to assess progress on this problem. The OD-test benchmark provides a straightforward means of comparison for methods that address the out-of-distribution sample detection problem. We present an exhaustive evaluation of a broad set of methods from related areas on image classification tasks. Furthermore, we show that for realistic applications of high-dimensional images, the existing methods have low accuracy. Our analysis reveals areas of strength and weakness of each method.

##### Abstract (translated by Google)
在现实世界中，学习系统可以接收看起来与训练期间看到的任何内容完全不同的输入，这可能导致不可预测的行为。因此，我们需要知道任何给定的输入是否属于训练数据的人口分布，以防止在已部署的系统中出现不可预测的行为。最近对这个问题的兴趣激增导致了深度学习文献中复杂技术的发展。但是，由于缺乏标准化的问题制定或详尽的评估，我们是否可以在实践中依赖这些方法并不明显。使这个问题与典型的监督学习环境不同的是，我们无法在实践中模拟分布式样本的多样性。训练中使用的异常值的分布可能与应用程序中遇到的异常值的分布不同。因此，仅使用两个数据集来学习内点与异常值的经典方法可以产生乐观的结果。我们引入OD-test，这是一个三数据集评估方案，作为评估该问题进展的实用且更可靠的策略。 OD测试基准为解决分布式样本检测问题的方法提供了直接的比较方法。我们对图像分类任务相关领域的一系列广泛方法进行了详尽的评估。此外，我们表明，对于高维图像的实际应用，现有方法具有低精度。我们的分析揭示了每种方法的优势和弱点。

##### URL
[http://arxiv.org/abs/1809.04729](http://arxiv.org/abs/1809.04729)

##### PDF
[http://arxiv.org/pdf/1809.04729](http://arxiv.org/pdf/1809.04729)

