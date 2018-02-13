---
layout: post
title: "Joint Learning for Pulmonary Nodule Segmentation, Attributes and Malignancy Prediction"
date: 2018-02-10 13:11:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Prediction
author: Botong Wu, Zhen Zhou, Jianwei Wang, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Refer to the literature of lung nodule classification, many studies adopt Convolutional Neural Networks (CNN) to directly predict the malignancy of lung nodules with original thoracic Computed Tomography (CT) and nodule location. However, these studies cannot tell how the CNN works in terms of predicting the malignancy of the given nodule, e.g., it's hard to conclude that whether the region within the nodule or the contextual information matters according to the output of the CNN. In this paper, we propose an interpretable and multi-task learning CNN -- Joint learning for \textbf{P}ulmonary \textbf{N}odule \textbf{S}egmentation \textbf{A}ttributes and \textbf{M}alignancy \textbf{P}rediction (PN-SAMP). It is able to not only accurately predict the malignancy of lung nodules, but also provide semantic high-level attributes as well as the areas of detected nodules. Moreover, the combination of nodule segmentation, attributes and malignancy prediction is helpful to improve the performance of each single task. In addition, inspired by the fact that radiologists often change window widths and window centers to help to make decision on uncertain nodules, PN-SAMP mixes multiple WW/WC together to gain information for the raw CT input images. To verify the effectiveness of the proposed method, the evaluation is implemented on the public LIDC-IDRI dataset, which is one of the largest dataset for lung nodule malignancy prediction. Experiments indicate that the proposed PN-SAMP achieves significant improvement with respect to lung nodule classification, and promising performance on lung nodule segmentation and attribute learning, compared with the-state-of-the-art methods.

##### Abstract (translated by Google)
参考文献肺结节分类，许多研究采用卷积神经网络（CNN）直接预测原发性胸部CT和结节位置的肺结节恶性程度。然而，这些研究无法说明CNN如何在预测给定结节的恶性肿瘤方面发挥作用，例如根据CNN的输出很难得出结节内的区域或上下文信息是否重要。在本文中，我们提出了一个可解释和多任务的学习CNN  - 联合学习，用于文本和文本{M}的比对和联合学习。 \ textbf {P} rediction（PN-SAMP）。它不仅能够准确预测肺结节的恶性程度，还能提供语义高级属性以及检测结节的区域。此外，结节分割，属性和恶性肿瘤预测的结合有助于提高每项任务的性能。此外，受放射科医师经常改变窗口宽度和窗口中心以帮助决定不确定结节的影响，PN-SAMP将多个WW / WC混合在一起以获取原始CT输入图像的信息。为了验证所提出的方法的有效性，评估在公众LIDC-IDRI数据集上实施，该数据集是用于肺结节恶性肿瘤预测的最大数据集之一。实验表明，与最先进的方法相比，所提出的PN-SAMP在肺结节分类方面获得显着改善，并且在肺结节分割和属性学习方面具有良好的性能。

##### URL
[http://arxiv.org/abs/1802.03584](http://arxiv.org/abs/1802.03584)

##### PDF
[http://arxiv.org/pdf/1802.03584](http://arxiv.org/pdf/1802.03584)

