---
layout: post
title: "Maximum Classifier Discrepancy for Unsupervised Domain Adaptation"
date: 2017-12-07 10:49:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Kuniaki Saito, Kohei Watanabe, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a method for unsupervised domain adaptation (UDA), where we aim to transfer knowledge from a label-rich domain (i.e., a source domain) to an unlabeled domain (i.e., a target domain). Many adversarial learning methods have been proposed for this task. These methods train domain classifier networks (i.e., a discriminator) to discriminate distinguish the features as either a source or target and train a feature generator network to mimic the discriminator.However, the domain classifier only tries to distinguish the features as a source or target and thus does not consider task-specific decision boundaries between classes. Therefore, a trained generator can generate ambiguous features near class boundaries. 
 To solve the problem, we propose a new approach that attempts to align distributions of source and target by utilizing the task-specific decision boundaries. We propose to utilize task-specific classifiers as discriminators that try to detect target samples that are far from the support of the source. A feature generator learns to generate target features inside the support to fool the classifiers. Since the generator uses feedback from task-specific classifiers, it avoids generating target features near class boundaries. Our method outperforms other methods on several datasets of image classification and semantic segmentation.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种无监督域自适应（UDA）的方法，我们的目标是将知识从一个标签丰富的域（即源域）转移到一个未标记的域（即一个目标域）。已经提出了许多对抗性的学习方法来完成这项任务。这些方法训练区域分类器网络（即鉴别器）区分将特征区分为源还是目标，并且训练特征生成器网络以模仿鉴别器。然而，分类器只尝试将特征区分为源或目标因此不考虑类之间的任务特定决策边界。因此，训练有素的发电机可以在班级边界附近产生模糊的特征。
 为了解决这个问题，我们提出了一种新的方法，试图通过利用任务特定的决策边界来调整源和目标的分布。我们建议利用任务特定的分类器作为鉴别器，试图检测远离源头支持的目标样本。特征生成器学习在支持内生成目标特征来欺骗分类器。由于生成器使用来自任务特定分类器的反馈，因此避免了在类边界附近生成目标特征。我们的方法在图像分类和语义分割的几个数据集上胜过其他方法。

##### URL
[http://arxiv.org/abs/1712.02560](http://arxiv.org/abs/1712.02560)

##### PDF
[http://arxiv.org/pdf/1712.02560](http://arxiv.org/pdf/1712.02560)

