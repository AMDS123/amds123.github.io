---
layout: post
title: "DeepPap: Deep Convolutional Networks for Cervical Cell Classification"
date: 2018-01-25 22:12:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Prediction Detection
author: Ling Zhang, Le Lu, Isabella Nogues, Ronald M. Summers, Shaoxiong Liu, Jianhua Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Automation-assisted cervical screening via Pap smear or liquid-based cytology (LBC) is a highly effective cell imaging based cancer detection tool, where cells are partitioned into "abnormal" and "normal" categories. However, the success of most traditional classification methods relies on the presence of accurate cell segmentations. Despite sixty years of research in this field, accurate segmentation remains a challenge in the presence of cell clusters and pathologies. Moreover, previous classification methods are only built upon the extraction of hand-crafted features, such as morphology and texture. This paper addresses these limitations by proposing a method to directly classify cervical cells - without prior segmentation - based on deep features, using convolutional neural networks (ConvNets). First, the ConvNet is pre-trained on a natural image dataset. It is subsequently fine-tuned on a cervical cell dataset consisting of adaptively re-sampled image patches coarsely centered on the nuclei. In the testing phase, aggregation is used to average the prediction scores of a similar set of image patches. The proposed method is evaluated on both Pap smear and LBC datasets. Results show that our method outperforms previous algorithms in classification accuracy (98.3%), area under the curve (AUC) (0.99) values, and especially specificity (98.3%), when applied to the Herlev benchmark Pap smear dataset and evaluated using five-fold cross-validation. Similar superior performances are also achieved on the HEMLBC (H&amp;E stained manual LBC) dataset. Our method is promising for the development of automation-assisted reading systems in primary cervical screening.

##### Abstract (translated by Google)
通过巴氏涂片或液基细胞学（LBC）进行的自动化辅助宫颈筛查是一种非常有效的基于细胞成像的癌症检测工具，其中细胞被划分为“异常”和“正常”类别。然而，大多数传统分类方法的成功依赖于准确细胞分割的存在。尽管在这个领域进行了六十年的研究，准确的分割仍然是细胞群和病理存在的挑战。而且，以前的分类方法只是建立在手工特征的提取上，如形态和纹理。本文通过提出一种基于深度特征的直接分类宫颈细胞的方法来解决这些局限性 - 使用卷积神经网络（ConvNets）。首先，ConvNet是在自然图像数据集上进行预先训练的。随后对宫颈细胞数据集进行微调，该数据集包括粗略地以细胞核为中心的自适应重新采样的图像片。在测试阶段，使用聚合来平均一组相似图像块的预测分数。所提出的方法在巴氏涂片和LBC数据集上进行评估。结果显示，应用Herlev基准巴氏涂片数据集时，我们的方法在分类准确率（98.3％），曲线下面积（AUC）（0.99）值，特别是特异性（98.3％）方面优于以前的算法，折叠交叉验证。 HEMLBC（H＆amp; E染色手册LBC）数据集也获得类似的优异性能。我们的方法是有希望的发展自动辅助阅读系统在初级宫颈癌筛查。

##### URL
[http://arxiv.org/abs/1801.08616](http://arxiv.org/abs/1801.08616)

##### PDF
[http://arxiv.org/pdf/1801.08616](http://arxiv.org/pdf/1801.08616)

