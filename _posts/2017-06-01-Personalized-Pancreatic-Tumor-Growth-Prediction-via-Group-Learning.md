---
layout: post
title: "Personalized Pancreatic Tumor Growth Prediction via Group Learning"
date: 2017-06-01 20:57:53
categories: arXiv_CV
tags: arXiv_CV CNN Inference Prediction
author: Ling Zhang, Le Lu, Ronald M. Summers, Electron Kebebew, Jianhua Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Tumor growth prediction, a highly challenging task, has long been viewed as a mathematical modeling problem, where the tumor growth pattern is personalized based on imaging and clinical data of a target patient. Though mathematical models yield promising results, their prediction accuracy may be limited by the absence of population trend data and personalized clinical characteristics. In this paper, we propose a statistical group learning approach to predict the tumor growth pattern that incorporates both the population trend and personalized data, in order to discover high-level features from multimodal imaging data. A deep convolutional neural network approach is developed to model the voxel-wise spatio-temporal tumor progression. The deep features are combined with the time intervals and the clinical factors to feed a process of feature selection. Our predictive model is pretrained on a group data set and personalized on the target patient data to estimate the future spatio-temporal progression of the patient's tumor. Multimodal imaging data at multiple time points are used in the learning, personalization and inference stages. Our method achieves a Dice coefficient of 86.8% +- 3.6% and RVD of 7.9% +- 5.4% on a pancreatic tumor data set, outperforming the DSC of 84.4% +- 4.0% and RVD 13.9% +- 9.8% obtained by a previous state-of-the-art model-based method.

##### Abstract (translated by Google)
肿瘤生长预测是一项非常具有挑战性的任务，长期以来一直被视为数学建模问题，其中肿瘤生长模式是基于目标患者的成像和临床数据进行个性化。尽管数学模型的结果令人满意，但由于缺乏人口趋势数据和个性化的临床特征，其预测准确性可能受到限制。在本文中，我们提出了统计组学习方法来预测包含人口趋势和个性化数据的肿瘤生长模式，以便从多模式成像数据中发现高级特征。深卷积神经网络方法被开发来模拟体素明智的时空肿瘤进展。将深度特征与时间间隔和临床因素相结合，提供特征选择过程。我们的预测模型预先在组数据集上进行预训练，并根据目标患者数据进行个性化处理，以估计患者肿瘤未来的时空进程。在多个时间点的多模式成像数据被用于学习，个性化和推理阶段。我们的方法在胰腺肿瘤数据集上获得了86.8％±3.6％的Dice系数和7.9％±5.4％的RVD系数，其优于84.4％±4.0％的DSC和13.9％±9.8％的RVD先前的最先进的基于模型的方法。

##### URL
[https://arxiv.org/abs/1706.00493](https://arxiv.org/abs/1706.00493)

##### PDF
[https://arxiv.org/pdf/1706.00493](https://arxiv.org/pdf/1706.00493)

