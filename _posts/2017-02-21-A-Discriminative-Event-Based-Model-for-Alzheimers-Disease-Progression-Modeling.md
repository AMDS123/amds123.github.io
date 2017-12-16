---
layout: post
title: "A Discriminative Event Based Model for Alzheimer's Disease Progression Modeling"
date: 2017-02-21 14:41:15
categories: arXiv_CV
tags: arXiv_CV GAN
author: Vikram Venkatraghavan, Esther Bron, Wiro Niessen, Stefan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
The event-based model (EBM) for data-driven disease progression modeling estimates the sequence in which biomarkers for a disease become abnormal. This helps in understanding the dynamics of disease progression and facilitates early diagnosis by staging patients on a disease progression timeline. Existing EBM methods are all generative in nature. In this work we propose a novel discriminative approach to EBM, which is shown to be more accurate as well as computationally more efficient than existing state-of-the art EBM methods. The method first estimates for each subject an approximate ordering of events, by ranking the posterior probabilities of individual biomarkers being abnormal. Subsequently, the central ordering over all subjects is estimated by fitting a generalized Mallows model to these approximate subject-specific orderings based on a novel probabilistic Kendall's Tau distance. To evaluate the accuracy, we performed extensive experiments on synthetic data simulating the progression of Alzheimer's disease. Subsequently, the method was applied to the Alzheimer's Disease Neuroimaging Initiative (ADNI) data to estimate the central event ordering in the dataset. The experiments benchmark the accuracy of the new model under various conditions and compare it with existing state-of-the-art EBM methods. The results indicate that discriminative EBM could be a simple and elegant approach to disease progression modeling.

##### Abstract (translated by Google)
用于数据驱动的疾病进展模型的基于事件的模型（EBM）估计疾病的生物标志物变得异常的顺序。这有助于了解疾病进展的动态，并通过在疾病进展时间表上对患者进行分期来促进早期诊断。现有的EBM方法本质上都是有生产力的。在这项工作中，我们提出了一种新颖的EBM方法，与现有技术的EBM方法相比，它显示出更精确，更高效的计算。该方法首先通过对各个生物标记异常的后验概率进行排序来针对每个受试者估计事件的近似排序。随后，所有主题的中心排序是通过拟合一个广义的Mallows模型到这些近似的主题特定的排序基于一个新的概率Kendall的Tau距离。为了评估准确性，我们对模拟阿尔茨海默病进展的合成数据进行了广泛的实验。随后，将该方法应用于阿尔茨海默氏病神经成像倡议（ADNI）数据以估计数据集中的中心事件排序。实验在各种条件下对新模型的准确性进行基准测试，并将其与现有的最先进的EBM方法进行比较。结果表明，有区别的EBM可能是一种简单而优雅的疾病进展建模方法。

##### URL
[https://arxiv.org/abs/1702.06408](https://arxiv.org/abs/1702.06408)

##### PDF
[https://arxiv.org/pdf/1702.06408](https://arxiv.org/pdf/1702.06408)

