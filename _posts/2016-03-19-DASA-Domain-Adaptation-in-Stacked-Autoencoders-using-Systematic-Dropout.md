---
layout: post
title: "DASA: Domain Adaptation in Stacked Autoencoders using Systematic Dropout"
date: 2016-03-19 07:27:56
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Abhijit Guha Roy, Debdoot Sheet
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation deals with adapting behaviour of machine learning based systems trained using samples in source domain to their deployment in target domain where the statistics of samples in both domains are dissimilar. The task of directly training or adapting a learner in the target domain is challenged by lack of abundant labeled samples. In this paper we propose a technique for domain adaptation in stacked autoencoder (SAE) based deep neural networks (DNN) performed in two stages: (i) unsupervised weight adaptation using systematic dropouts in mini-batch training, (ii) supervised fine-tuning with limited number of labeled samples in target domain. We experimentally evaluate performance in the problem of retinal vessel segmentation where the SAE-DNN is trained using large number of labeled samples in the source domain (DRIVE dataset) and adapted using less number of labeled samples in target domain (STARE dataset). The performance of SAE-DNN measured using $logloss$ in source domain is $0.19$, without and with adaptation are $0.40$ and $0.18$, and $0.39$ when trained exclusively with limited samples in target domain. The area under ROC curve is observed respectively as $0.90$, $0.86$, $0.92$ and $0.87$. The high efficiency of vessel segmentation with DASA strongly substantiates our claim.

##### Abstract (translated by Google)
域适应涉及使用源域中的样本训练的基于机器学习的系统的行为适应其在两个域中的样本统计不同的目标域中的部署。直接培训或适应目标领域的学习者的任务受到缺乏丰富标签样本的挑战。在本文中，我们提出了一种基于堆叠自编码器（SAE）的深度神经网络（DNN）中的领域自适应技术，分为两个阶段：（i）使用小批量训练中的系统退出的无监督权重自适应;（ii）监督微调目标域中有限数量的标记样本。我们通过在源域（DRIVE数据集）中使用大量标记样本训练SAE-DNN并在目标域（STARE数据集）中使用较少数量的标记样本进行适应性训练来实验评估视网膜血管分割问题中的性能。在源域中使用$ logloss $测量的SAE-DNN的性能是$ 0.19 $，没有和有适应性的情况下是$ 0.40 $和$ 0.18 $，以及$ 0.39 $在目标域中仅使用有限样本进行训练时的性能。 ROC曲线下面积分别为$ 0.90 $，$ 0.86 $，$ 0.92 $和$ 0.87 $。用DASA进行血管分割的高效率证实了我们的主张。

##### URL
[https://arxiv.org/abs/1603.06060](https://arxiv.org/abs/1603.06060)

##### PDF
[https://arxiv.org/pdf/1603.06060](https://arxiv.org/pdf/1603.06060)

