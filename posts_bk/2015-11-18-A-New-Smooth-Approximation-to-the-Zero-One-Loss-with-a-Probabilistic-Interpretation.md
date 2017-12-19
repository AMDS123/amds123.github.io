---
layout: post
title: "A New Smooth Approximation to the Zero One Loss with a Probabilistic Interpretation"
date: 2015-11-18 02:31:16
categories: arXiv_CV
tags: arXiv_CV Review Sparse Optimization Inference Prediction Gradient_Descent
author: Md Kamrul Hasan, Christopher J. Pal
mathjax: true
---

* content
{:toc}

##### Abstract
We examine a new form of smooth approximation to the zero one loss in which learning is performed using a reformulation of the widely used logistic function. Our approach is based on using the posterior mean of a novel generalized Beta-Bernoulli formulation. This leads to a generalized logistic function that approximates the zero one loss, but retains a probabilistic formulation conferring a number of useful properties. The approach is easily generalized to kernel logistic regression and easily integrated into methods for structured prediction. We present experiments in which we learn such models using an optimization method consisting of a combination of gradient descent and coordinate descent using localized grid search so as to escape from local minima. Our experiments indicate that optimization quality is improved when learning meta-parameters are themselves optimized using a validation set. Our experiments show improved performance relative to widely used logistic and hinge loss methods on a wide variety of problems ranging from standard UC Irvine and libSVM evaluation datasets to product review predictions and a visual information extraction task. We observe that the approach: 1) is more robust to outliers compared to the logistic and hinge losses; 2) outperforms comparable logistic and max margin models on larger scale benchmark problems; 3) when combined with Gaussian- Laplacian mixture prior on parameters the kernelized version of our formulation yields sparser solutions than Support Vector Machine classifiers; and 4) when integrated into a probabilistic structured prediction technique our approach provides more accurate probabilities yielding improved inference and increasing information extraction performance.

##### Abstract (translated by Google)
我们研究一种新的形式，使用广泛使用的逻辑函数的重新表达来实现学习的零损失。我们的方法基于使用新的广义Beta-Bernoulli公式的后验均值。这导致了一个近似于一个零损失的广义逻辑函数，但保留了赋予许多有用特性的概率公式。该方法很容易推广到内核逻辑回归，并容易集成到结构化预测方法中。我们目前的实验中，我们学习这样的模型，使用由梯度下降和坐标下降组合使用局部网格搜索组合的优化方法，以逃离局部最小值。我们的实验表明，当学习元参数本身使用验证集优化时，优化质量得到改善。我们的实验显示相对于广泛使用的逻辑和铰链损失方法在从标准的UC Irvine和libSVM评估数据集到产品评论预测和视觉信息提取任务等各种各样的问题上改进的性能。我们观察到这样的方法：1）与逻辑和铰链损失相比，对于异常值更为稳健; 2）在更大规模的基准测试问题上胜过可比较的物流和最大利润率模型; 3）当与参数之前的高斯 - 拉普拉斯混合结合时，我们的配方的核化版本产生比支持向量机分类器更稀疏的解决方案;以及4）当将其整合为概率结构化预测技术时，我们的方法提供更准确的概率，从而产生改进的推断和提高的信息提取性能。

##### URL
[https://arxiv.org/abs/1511.05643](https://arxiv.org/abs/1511.05643)

##### PDF
[https://arxiv.org/pdf/1511.05643](https://arxiv.org/pdf/1511.05643)

