---
layout: post
title: "Subspace Selection to Suppress Confounding Source Domain Information in AAM Transfer Learning"
date: 2017-10-03 18:26:16
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Face Transfer_Learning
author: Azin Asgarian, Ahmed Bilal Ashraf, David Fleet, Babak Taati
mathjax: true
---

* content
{:toc}

##### Abstract
Active appearance models (AAMs) are a class of generative models that have seen tremendous success in face analysis. However, model learning depends on the availability of detailed annotation of canonical landmark points. As a result, when accurate AAM fitting is required on a different set of variations (expression, pose, identity), a new dataset is collected and annotated. To overcome the need for time consuming data collection and annotation, transfer learning approaches have received recent attention. The goal is to transfer knowledge from previously available datasets (source) to a new dataset (target). We propose a subspace transfer learning method, in which we select a subspace from the source that best describes the target space. We propose a metric to compute the directional similarity between the source eigenvectors and the target subspace. We show an equivalence between this metric and the variance of target data when projected onto source eigenvectors. Using this equivalence, we select a subset of source principal directions that capture the variance in target data. To define our model, we augment the selected source subspace with the target subspace learned from a handful of target examples. In experiments done on six publicly available datasets, we show that our approach outperforms the state of the art in terms of the RMS fitting error as well as the percentage of test examples for which AAM fitting converges to the ground truth.

##### Abstract (translated by Google)
活动外观模型（AAMs）是一类在脸部分析方面取得巨大成功的生成模型。但是，模型学习取决于经典标志点的详细注释的可用性。因此，当需要在不同的一组变量（表达，姿势，身份）上进行精确的AAM拟合时，会收集并注释一个新的数据集。为了克服耗时的数据收集和标注的需要，转移学习方法近来受到关注。目标是将知识从以前可用的数据集（源）传输到新的数据集（目标）。我们提出了一个子空间转移学习方法，在这个方法中我们从源头中选择一个最能描述目标空间的子空间。我们提出一个度量来计算源特征向量和目标子空间之间的方向相似度。当投影到源特征向量上时，我们展示了这个度量和目标数据方差之间的等价性。使用这种等价性，我们选择一组源目标方向来捕获目标数据中的方差。为了定义我们的模型，我们用从一些目标例子中学习的目标子空间来扩充选择的源子空间。在六个公开可用的数据集上进行的实验中，我们表明，我们的方法在RMS拟合误差以及AAM拟合收敛于地面实况的测试示例的百分比方面优于现有技术。

##### URL
[https://arxiv.org/abs/1708.08508](https://arxiv.org/abs/1708.08508)

##### PDF
[https://arxiv.org/pdf/1708.08508](https://arxiv.org/pdf/1708.08508)

