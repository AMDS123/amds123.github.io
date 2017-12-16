---
layout: post
title: "Predicting 1p19q Chromosomal Deletion of Low-Grade Gliomas from MR Images using Deep Learning"
date: 2016-11-21 18:43:20
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Deep_Learning
author: Zeynettin Akkus, Issa Ali, Jiri Sedlar, Timothy L. Kline, Jay P. Agrawal, Ian F. Parney, Caterina Giannini, Bradley J. Erickson
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Several studies have associated codeletion of chromosome arms 1p/19q in low-grade gliomas (LGG) with positive response to treatment and longer progression free survival. Therefore, predicting 1p/19q status is crucial for effective treatment planning of LGG. In this study, we predict the 1p/19q status from MR images using convolutional neural networks (CNN), which could be a noninvasive alternative to surgical biopsy and histopathological analysis. Method: Our method consists of three main steps: image registration, tumor segmentation, and classification of 1p/19q status using CNN. We included a total of 159 LGG with 3 image slices each who had biopsy-proven 1p/19q status (57 nondeleted and 102 codeleted) and preoperative postcontrast-T1 (T1C) and T2 images. We divided our data into training, validation, and test sets. The training data was balanced for equal class probability and then augmented with iterations of random translational shift, rotation, and horizontal and vertical flips to increase the size of the training set. We shuffled and augmented the training data to counter overfitting in each epoch. Finally, we evaluated several configurations of a multi-scale CNN architecture until training and validation accuracies became consistent. Results: The results of the best performing configuration on the unseen test set were 93.3% (sensitivity), 82.22% (specificity), and 87.7% (accuracy). Conclusion: Multi-scale CNN with their self-learning capability provides promising results for predicting 1p/19q status noninvasively based on T1C and T2 images. Significance: Predicting 1p/19q status noninvasively from MR images would allow selecting effective treatment strategies for LGG patients without the need for surgical biopsy.

##### Abstract (translated by Google)
目的：一些研究已经将低级胶质瘤（LGG）染色体臂1p / 19q的密码子与治疗阳性和无进展生存时间延长联系起来。因此，预测1p / 19q状态对LGG有效的治疗计划至关重要。在这项研究中，我们使用卷积神经网络（CNN）预测MR图像的1p / 19q状态，这可能是手术活检和组织病理学分析的非侵入性替代方法。方法：我们的方法由三个主要步骤组成：图像配准，肿瘤分割，以及使用CNN对1p / 19q状态进行分类。我们包括总共159个LGG和3个图像切片，每个图像切片具有活检证实的1p / 19q状态（57个未删除和102个编码）和术前后对比T1（T1C）和T2图像。我们将数据分成训练，验证和测试集。训练数据在相同的类别概率下平衡，然后用随机平移，旋转，水平和垂直翻转的迭代来增加训练集的大小。我们洗牌并增加了训练数据来对付每个时代的过度训练。最后，我们评估了多尺度的CNN架构的几种配置，直到训练和验证的准确性变得一致。结果：未见试验组的最佳表现结果的结果为93.3％（灵敏度），82.22％（特异性）和87.7％（准确度）。结论：多尺度CNN具有自学习能力，对T1C和T2图像非侵入性预测1p / 19q状态具有良好的预测效果。意义：从MR图像非侵入性地预测1p / 19q状态将允许为LGG患者选择有效的治疗策略而不需要手术活检。

##### URL
[https://arxiv.org/abs/1611.06939](https://arxiv.org/abs/1611.06939)

##### PDF
[https://arxiv.org/pdf/1611.06939](https://arxiv.org/pdf/1611.06939)

