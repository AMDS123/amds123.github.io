---
layout: post
title: "Out-of-Distribution Detection Using an Ensemble of Self Supervised Leave-out Classifiers"
date: 2018-09-04 16:00:08
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Detection
author: Apoorv Vyas, Nataraj Jammalamadaka, Xia Zhu, Dipankar Das, Bharat Kaul, Theodore L. Willke
mathjax: true
---

* content
{:toc}

##### Abstract
As deep learning methods form a critical part in commercially important applications such as autonomous driving and medical diagnostics, it is important to reliably detect out-of-distribution (OOD) inputs while employing these algorithms. In this work, we propose an OOD detection algorithm which comprises of an ensemble of classifiers. We train each classifier in a self-supervised manner by leaving out a random subset of training data as OOD data and the rest as in-distribution (ID) data. We propose a novel margin-based loss over the softmax output which seeks to maintain at least a margin $m$ between the average entropy of the OOD and in-distribution samples. In conjunction with the standard cross-entropy loss, we minimize the novel loss to train an ensemble of classifiers. We also propose a novel method to combine the outputs of the ensemble of classifiers to obtain OOD detection score and class prediction. Overall, our method convincingly outperforms Hendrycks et al.[7] and the current state-of-the-art ODIN[13] on several OOD detection benchmarks.

##### Abstract (translated by Google)
由于深度学习方法是商业上重要应用（如自动驾驶和医疗诊断）的关键部分，因此在采用这些算法时可靠地检测分布外（OOD）输入非常重要。在这项工作中，我们提出了一种OOD检测算法，它包括一组分类器。我们以自我监督的方式训练每个分类器，将训练数据的随机子集省略为OOD数据，其余的作为分发（ID）数据。我们提出了一种新的基于保证金的软损失输出，它试图在OOD和分配样本的平均熵之间保持至少一个保证金$ m $。结合标准的交叉熵损失，我们将新的损失最小化，以训练一组分类器。我们还提出了一种新的方法来组合分类器集合的输出，以获得OOD检测分数和类预测。总的来说，我们的方法令人信服地胜过Hendrycks等[7]。以及目前最先进的ODIN [13]在几个OOD检测基准上。

##### URL
[http://arxiv.org/abs/1809.03576](http://arxiv.org/abs/1809.03576)

##### PDF
[http://arxiv.org/pdf/1809.03576](http://arxiv.org/pdf/1809.03576)

