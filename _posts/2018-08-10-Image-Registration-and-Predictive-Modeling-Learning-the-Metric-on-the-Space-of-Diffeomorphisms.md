---
layout: post
title: "Image Registration and Predictive Modeling: Learning the Metric on the Space of Diffeomorphisms"
date: 2018-08-10 15:25:10
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Classification
author: Ayagoz Mussabayeva, Alexey Kroshnin, Anvar Kurmukov, Yulia Dodonova, Li Shen, Shan Cong, Lei Wang, Boris A. Gutman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for metric optimization in the Large Deformation Diffeomorphic Metric Mapping (LDDMM) framework, by treating the induced Riemannian metric on the space of diffeomorphisms as a kernel in a machine learning context. For simplicity, we choose the kernel Fischer Linear Discriminant Analysis (KLDA) as the framework. Optimizing the kernel parameters in an Expectation-Maximization framework, we define model fidelity via the hinge loss of the decision function. The resulting algorithm optimizes the parameters of the LDDMM norm-inducing differential operator as a solution to a group-wise registration and classification problem. In practice, this may lead to a biology-aware registration, focusing its attention on the predictive task at hand such as identifying the effects of disease. We first tested our algorithm on a synthetic dataset, showing that our parameter selection improves registration quality and classification accuracy. We then tested the algorithm on 3D subcortical shapes from the Schizophrenia cohort Schizconnect. Our Schizpohrenia-Control predictive model showed significant improvement in ROC AUC compared to baseline parameters.

##### Abstract (translated by Google)
我们提出了一种在大变形微分形态度量映射（LDDMM）框架中进行度量优化的方法，通过将微分同胚的空间上的诱导黎曼度量作为机器学习环境中的核来处理。为简单起见，我们选择内核Fischer线性判别分析（KLDA）作为框架。在Expectation-Maximization框架中优化内核参数，我们通过决策函数的铰链损失来定义模型保真度。得到的算法优化LDDMM范数诱导微分算子的参数，作为分组登记和分类问题的解决方案。在实践中，这可能导致生物学意识的注册，将注意力集中在手头的预测任务上，例如识别疾病的影响。我们首先在合成数据集上测试我们的算法，表明我们的参数选择提高了注册质量和分类准确性。然后，我们从精神分裂症队列Schizconnect测试了3D皮质下形状的算法。我们的Schizpohrenia-Control预测模型显示与基线参数相比ROC AUC显着改善。

##### URL
[http://arxiv.org/abs/1808.04439](http://arxiv.org/abs/1808.04439)

##### PDF
[http://arxiv.org/pdf/1808.04439](http://arxiv.org/pdf/1808.04439)

