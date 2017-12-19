---
layout: post
title: "Fine-grained pose prediction, normalization, and recognition"
date: 2015-11-22 20:32:45
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction Recognition
author: Ning Zhang, Evan Shelhamer, Yang Gao, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Pose variation and subtle differences in appearance are key challenges to fine-grained classification. While deep networks have markedly improved general recognition, many approaches to fine-grained recognition rely on anchoring networks to parts for better accuracy. Identifying parts to find correspondence discounts pose variation so that features can be tuned to appearance. To this end previous methods have examined how to find parts and extract pose-normalized features. These methods have generally separated fine-grained recognition into stages which first localize parts using hand-engineered and coarsely-localized proposal features, and then separately learn deep descriptors centered on inferred part positions. We unify these steps in an end-to-end trainable network supervised by keypoint locations and class labels that localizes parts by a fully convolutional network to focus the learning of feature representations for the fine-grained classification task. Experiments on the popular CUB200 dataset show that our method is state-of-the-art and suggest a continuing role for strong supervision.

##### Abstract (translated by Google)
姿态变化和外观上的微妙差异是细粒度分类的关键挑战。尽管深度网络显着提高了总体识别率，但是许多细粒度识别方法依赖于将网络锚定到零件以获得更好的准确性。识别零件以查找对应折扣构成变化，以便可以将特征调整为外观。为此，以前的方法已经研究了如何找到零件并提取姿态规范化的特征。这些方法通常将细粒度识别分为几个阶段，首先使用手工设计和粗略局部化的提议特征定位零件，然后分别学习以推测零件位置为中心的深度描述符。我们将这些步骤统一在由关键点位置和类标签监督的端到端可训练网络中，这些标签通过完全卷积网络对部分进行定位，以聚焦细分类别任务的特征表示的学习。流行的CUB200数据集上的实验表明，我们的方法是最先进的，并提出了强有力的监督的持续作用。

##### URL
[https://arxiv.org/abs/1511.07063](https://arxiv.org/abs/1511.07063)

##### PDF
[https://arxiv.org/pdf/1511.07063](https://arxiv.org/pdf/1511.07063)

