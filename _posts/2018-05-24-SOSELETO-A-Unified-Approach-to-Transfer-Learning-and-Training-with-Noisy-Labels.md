---
layout: post
title: "SOSELETO: A Unified Approach to Transfer Learning and Training with Noisy Labels"
date: 2018-05-24 12:03:58
categories: arXiv_AI
tags: arXiv_AI Regularization Transfer_Learning Optimization Classification
author: Or Litany, Daniel Freedman
mathjax: true
---

* content
{:toc}

##### Abstract
We present SOSELETO (SOurce SELEction for Target Optimization), a new method for exploiting a source dataset to solve a classification problem on a target dataset. SOSELETO is based on the following simple intuition: some source examples are more informative than others for the target problem. To capture this intuition, source samples are each given weights; these weights are solved for jointly with the source and target classification problems via a bilevel optimization scheme. The target therefore gets to choose the source samples which are most informative for its own classification task. Furthermore, the bilevel nature of the optimization acts as a kind of regularization on the target, mitigating overfitting. SOSELETO may be applied to both classic transfer learning, as well as the problem of training on datasets with noisy labels; we show state of the art results on both of these problems.

##### Abstract (translated by Google)
我们提出了SOSELETO（SOURCE SELEction用于目标优化），一种利用源数据集来解决目标数据集分类问题的新方法。 SOSELETO基于以下简单的直觉：对于目标问题，一些源例子比其他例子更具信息性。为了捕捉这种直觉，源样本每个都给予权重;这些权重通过双层优化方案与源和目标分类问题联合解决。因此，目标可以选择对自己的分类任务来说信息最丰富的源样本。此外，优化的双层性质是对目标的正规化，缓解过度拟合。 SOSELETO可能适用于经典转移学习以及带有噪音标签的数据集的训练问题;我们展示了这两个问题的最新成果。

##### URL
[http://arxiv.org/abs/1805.09622](http://arxiv.org/abs/1805.09622)

##### PDF
[http://arxiv.org/pdf/1805.09622](http://arxiv.org/pdf/1805.09622)

