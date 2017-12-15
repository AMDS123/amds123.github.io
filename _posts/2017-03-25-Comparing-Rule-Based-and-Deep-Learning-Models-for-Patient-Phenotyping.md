---
layout: post
title: "Comparing Rule-Based and Deep Learning Models for Patient Phenotyping"
date: 2017-03-25 15:37:09
categories: arXiv_SD
tags: arXiv_SD Salient CNN Classification Deep_Learning Prediction
author: Sebastian Gehrmann, Franck Dernoncourt, Yeran Li, Eric T. Carlson, Joy T. Wu, Jonathan Welt, John Foote Jr., Edward T. Moseley, David W. Grant, Patrick D. Tyler, Leo Anthony Celi
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: We investigate whether deep learning techniques for natural language processing (NLP) can be used efficiently for patient phenotyping. Patient phenotyping is a classification task for determining whether a patient has a medical condition, and is a crucial part of secondary analysis of healthcare data. We assess the performance of deep learning algorithms and compare them with classical NLP approaches. Materials and Methods: We compare convolutional neural networks (CNNs), n-gram models, and approaches based on cTAKES that extract pre-defined medical concepts from clinical notes and use them to predict patient phenotypes. The performance is tested on 10 different phenotyping tasks using 1,610 discharge summaries extracted from the MIMIC-III database. Results: CNNs outperform other phenotyping algorithms in all 10 tasks. The average F1-score of our model is 76 (PPV of 83, and sensitivity of 71) with our model having an F1-score up to 37 points higher than alternative approaches. We additionally assess the interpretability of our model by presenting a method that extracts the most salient phrases for a particular prediction. Conclusion: We show that NLP methods based on deep learning improve the performance of patient phenotyping. Our CNN-based algorithm automatically learns the phrases associated with each patient phenotype. As such, it reduces the annotation complexity for clinical domain experts, who are normally required to develop task-specific annotation rules and identify relevant phrases. Our method performs well in terms of both performance and interpretability, which indicates that deep learning is an effective approach to patient phenotyping based on clinicians' notes.

##### Abstract (translated by Google)
目的：我们研究自然语言处理（NLP）的深度学习技术是否可以有效地用于患者表型分型。患者表型分型是确定患者是否具有医疗状况的分类任务，并且是医疗数据的二次分析的关键部分。我们评估深度学习算法的性能，并将其与经典的NLP方法进行比较。材料和方法：我们比较了卷积神经网络（CNN），n-gram模型和基于cTAKES的方法，这些方法从临床笔记中提取预定义的医学概念，并用它们来预测患者的表型。性能在10个不同的表型任务上进行测试，使用从MIMIC-III数据库中提取的1,610个出院总结。结果：在所有10个任务中CNN都优于其他表型分析算法。我们模型的平均F1分数为76（PPV为83，灵敏度为71），F1分数高于其他方法的37分。我们另外通过提出一种方法来评估我们模型的可解释性，该方法为特定预测提取最显着的短语。结论：我们表明，基于深度学习的NLP方法提高了患者表型的表现。我们的基于CNN的算法自动学习与每个患者表型相关的短语。因此，它降低了临床领域专家的注解复杂性，临床领域专家通常需要开发特定于任务的注释规则并识别相关短语。我们的方法在表现和可解释性方面表现良好，这表明根据临床医生的笔记，深度学习是一种有效的患者表型分析方法。

##### URL
[https://arxiv.org/abs/1703.08705](https://arxiv.org/abs/1703.08705)

##### PDF
[https://arxiv.org/pdf/1703.08705](https://arxiv.org/pdf/1703.08705)

