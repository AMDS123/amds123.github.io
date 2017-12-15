---
layout: post
title: "De-identification of Patient Notes with Recurrent Neural Networks"
date: 2016-06-10 20:45:30
categories: arXiv_CL
tags: arXiv_CL RNN
author: Franck Dernoncourt, Ji Young Lee, Ozlem Uzuner, Peter Szolovits
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Patient notes in electronic health records (EHRs) may contain critical information for medical investigations. However, the vast majority of medical investigators can only access de-identified notes, in order to protect the confidentiality of patients. In the United States, the Health Insurance Portability and Accountability Act (HIPAA) defines 18 types of protected health information (PHI) that needs to be removed to de-identify patient notes. Manual de-identification is impractical given the size of EHR databases, the limited number of researchers with access to the non-de-identified notes, and the frequent mistakes of human annotators. A reliable automated de-identification system would consequently be of high value. Materials and Methods: We introduce the first de-identification system based on artificial neural networks (ANNs), which requires no handcrafted features or rules, unlike existing systems. We compare the performance of the system with state-of-the-art systems on two datasets: the i2b2 2014 de-identification challenge dataset, which is the largest publicly available de-identification dataset, and the MIMIC de-identification dataset, which we assembled and is twice as large as the i2b2 2014 dataset. Results: Our ANN model outperforms the state-of-the-art systems. It yields an F1-score of 97.85 on the i2b2 2014 dataset, with a recall 97.38 and a precision of 97.32, and an F1-score of 99.23 on the MIMIC de-identification dataset, with a recall 99.25 and a precision of 99.06. Conclusion: Our findings support the use of ANNs for de-identification of patient notes, as they show better performance than previously published systems while requiring no feature engineering.

##### Abstract (translated by Google)
目标：电子健康记录（EHR）中的患者笔记可能包含关于医学调查的重要信息。但是，绝大多数医疗调查人员只能访问脱识的票据，以保护患者的机密性。在美国，“健康保险流通与责任法案”（HIPAA）定义了18种需要删除的受保护的健康信息（PHI），以便识别病人笔记。考虑到EHR数据库的规模，有限数量的研究人员能够访问未被识别的笔记以及人类注释者经常犯的错误，手动去识别是不切实际的。一个可靠的自动去识别系统因此具有很高的价值。材料和方法：我们引入了第一个基于人工神经网络（ANN）的去识别系统，与现有系统不同，它不需要手工特征或规则。我们将系统的性能与最先进的系统的性能进行了比较：i2b2 2014去识别挑战数据集（最大的公开可用的去识别数据集）和MIMIC去识别数据集并且是i2b2 2014数据集的两倍。结果：我们的人工神经网络模型胜过最先进的系统。它在i2b2 2014数据集上获得了97.85的F1分值，回忆97.38，精度97.32，MIMIC去识别数据集的F1分数为99.23，回忆率99.25，精度99.06。结论：我们的研究结果支持使用人工神经网络去识别病人笔记，因为他们表现出比以前发表的系统更好的性能，而不需要特征工程。

##### URL
[https://arxiv.org/abs/1606.03475](https://arxiv.org/abs/1606.03475)

##### PDF
[https://arxiv.org/pdf/1606.03475](https://arxiv.org/pdf/1606.03475)

