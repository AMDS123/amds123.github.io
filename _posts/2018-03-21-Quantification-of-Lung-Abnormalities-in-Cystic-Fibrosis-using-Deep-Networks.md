---
layout: post
title: "Quantification of Lung Abnormalities in Cystic Fibrosis using Deep Networks"
date: 2018-03-21 16:18:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Filipe Marques, Florian Dubost, Mariette Kemner-van de Corput, Harm A.W. Tiddens, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Cystic fibrosis is a genetic disease which may appear in early life with structural abnormalities in lung tissues. We propose to detect these abnormalities using a texture classification approach. Our method is a cascade of two convolutional neural networks. The first network detects the presence of abnormal tissues. The second network identifies the type of the structural abnormalities: bronchiectasis, atelectasis or mucus plugging.We also propose a network computing pixel-wise heatmaps of abnormality presence learning only from the patch-wise annotations. Our database consists of CT scans of 194 subjects. We use 154 subjects to train our algorithms and the 40 remaining ones as a test set. We compare our method with random forest and a single neural network approach. The first network reaches an accuracy of 0,94 for disease detection, 0,18 higher than the random forest classifier and 0,37 higher than the single neural network. Our cascade approach yields a final class-averaged F1-score of 0,33, outperforming the baseline method and the single network by 0,10 and 0,12.

##### Abstract (translated by Google)
囊性纤维化是一种早期可能出现的遗传性疾病，伴有肺组织结构异常。我们建议使用纹理分类方法来检测这些异常。我们的方法是两个卷积神经网络的级联。第一个网络检测到异常组织的存在。第二个网络识别结构异常的类型：支气管扩张，肺不张或粘液堵塞。我们还提出了一种网络计算异常存在学习的像素热图，只能从补丁明智的注释中学习。我们的数据库由194个科目的CT扫描组成。我们使用154个科目来训练我们的算法，并将剩余的40个作为测试集。我们将我们的方法与随机森林和单个神经网络方法进行比较。第一个网络的疾病检测准确率为0.94，比随机森林分类器高0.18，比单一神经网络高0.37。我们的级联方法得出最终的班级平均F1分数为0.33，优于基线方法和单一网络，分别为0,10和0.12。

##### URL
[http://arxiv.org/abs/1803.07991](http://arxiv.org/abs/1803.07991)

##### PDF
[http://arxiv.org/pdf/1803.07991](http://arxiv.org/pdf/1803.07991)

