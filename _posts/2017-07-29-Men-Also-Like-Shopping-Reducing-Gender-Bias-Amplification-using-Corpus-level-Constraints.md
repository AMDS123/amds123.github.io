---
layout: post
title: "Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints"
date: 2017-07-29 03:38:32
categories: arXiv_CL
tags: arXiv_CL Inference Classification Prediction Relation Recognition
author: Jieyu Zhao, Tianlu Wang, Mark Yatskar, Vicente Ordonez, Kai-Wei Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Language is increasingly being used to define rich visual recognition problems with supporting image collections sourced from the web. Structured prediction models are used in these tasks to take advantage of correlations between co-occurring labels and visual input but risk inadvertently encoding social biases found in web corpora. In this work, we study data and models associated with multilabel object classification and visual semantic role labeling. We find that (a) datasets for these tasks contain significant gender bias and (b) models trained on these datasets further amplify existing bias. For example, the activity cooking is over 33% more likely to involve females than males in a training set, and a trained model further amplifies the disparity to 68% at test time. We propose to inject corpus-level constraints for calibrating existing structured prediction models and design an algorithm based on Lagrangian relaxation for collective inference. Our method results in almost no performance loss for the underlying recognition task but decreases the magnitude of bias amplification by 47.5% and 40.5% for multilabel classification and visual semantic role labeling, respectively.

##### Abstract (translated by Google)
语言越来越多地被用来定义丰富的视觉识别问题，支持来自网络的图像集合。在这些任务中使用结构化预测模型来利用共现标签和视觉输入之间的相关性，但是可能无意中编码在网络语料库中发现的社会偏见。在这项工作中，我们研究与多标签对象分类和视觉语义角色标签相关的数据和模型。我们发现（a）这些任务的数据集包含显着的性别偏见和（b）对这些数据集进行培训的模型进一步放大了现有的偏见。例如，在训练组中，活动烹饪的可能性比男性高出33％以上，而训练有素的模型在测试时间将差距进一步放大到68％。我们建议注入语料级约束来校准现有的结构化预测模型，并设计基于拉格朗日松弛的算法来进行集体推理。我们的方法在基本的识别任务中几乎没有性能损失，但是对于多标签分类和视觉语义角色标注，偏差放大的幅度分别降低了47.5％和40.5％。

##### URL
[https://arxiv.org/abs/1707.09457](https://arxiv.org/abs/1707.09457)

##### PDF
[https://arxiv.org/pdf/1707.09457](https://arxiv.org/pdf/1707.09457)

