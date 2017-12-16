---
layout: post
title: "RECOD Titans at ISIC Challenge 2017"
date: 2017-03-14 23:11:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Detection
author: Afonso Menegola, Julia Tavares, Michel Fornaciali, Lin Tzy Li, Sandra Avila, Eduardo Valle
mathjax: true
---

* content
{:toc}

##### Abstract
This extended abstract describes the participation of RECOD Titans in parts 1 and 3 of the ISIC Challenge 2017 "Skin Lesion Analysis Towards Melanoma Detection" (ISBI 2017). Although our team has a long experience with melanoma classification, the ISIC Challenge 2017 was the very first time we worked on skin-lesion segmentation. For part 1 (segmentation), our final submission used four of our models: two trained with all 2000 samples, without a validation split, for 250 and for 500 epochs respectively; and other two trained and validated with two different 1600/400 splits, for 220 epochs. Those four models, individually, achieved between 0.780 and 0.783 official validation scores. Our final submission averaged the output of those four models achieved a score of 0.793. For part 3 (classification), the submitted test run as well as our last official validation run were the result from a meta-model that assembled seven base deep-learning models: three based on Inception-V4 trained on our largest dataset; three based on Inception trained on our smallest dataset; and one based on ResNet-101 trained on our smaller dataset. The results of those component models were stacked in a meta-learning layer based on an SVM trained on the validation set of our largest dataset.

##### Abstract (translated by Google)
本扩展摘要描述了RECOD Titans参与ISIC挑战赛2017“皮肤病变分析对黑色素瘤检测”（ISBI 2017）第1和3部分的参与情况。尽管我们的团队在黑色素瘤分类方面有着长期的经验，但“ISIC挑战赛2017”是我们第一次进行皮肤病灶分割。对于第一部分（分割），我们的最终提交使用了我们的四个模型：两个训练了2000个样本，没有验证分割，分别为250和500个时期;另外两人训练和验证两个不同的1600/400分裂，为220个纪元。这四个模型分别取得0.780和0.783官方验证分数。我们最后的提交文件平均得出这四个模型的得分为0.793。对于第3部分（分类），提交的测试运行以及我们上一次正式的验证运行是组合七个基础深度学习模型的元模型的结果：三个基于对最大数据集进行训练的Inception-V4;三个基于最小数据集的Inception训练;和一个基于ResNet-101的小型数据集进行训练。这些组件模型的结果被叠加在一个基于我们最大的数据集的验证集训练的SVM的元学习层。

##### URL
[https://arxiv.org/abs/1703.04819](https://arxiv.org/abs/1703.04819)

##### PDF
[https://arxiv.org/pdf/1703.04819](https://arxiv.org/pdf/1703.04819)

