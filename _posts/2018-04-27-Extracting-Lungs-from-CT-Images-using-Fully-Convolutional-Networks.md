---
layout: post
title: "Extracting Lungs from CT Images using Fully Convolutional Networks"
date: 2018-04-27 22:27:06
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Jeovane Honório Alves, Pedro Martins Moreira Neto, Lucas Ferrari de Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
Analysis of cancer and other pathological diseases, like the interstitial lung diseases (ILDs), is usually possible through Computed Tomography (CT) scans. To aid this, a preprocessing step of segmentation is performed to reduce the area to be analyzed, segmenting the lungs and removing unimportant regions. Generally, complex methods are developed to extract the lung region, also using hand-made feature extractors to enhance segmentation. With the popularity of deep learning techniques and its automated feature learning, we propose a lung segmentation approach using fully convolutional networks (FCNs) combined with fully connected conditional random fields (CRF), employed in many state-of-the-art segmentation works. Aiming to develop a generalized approach, the publicly available datasets from University Hospitals of Geneva (HUG) and VESSEL12 challenge were studied, including many healthy and pathological CT scans for evaluation. Experiments using the dataset individually, its trained model on the other dataset and a combination of both datasets were employed. Dice scores of $98.67\%\pm0.94\%$ for the HUG-ILD dataset and $99.19\%\pm0.37\%$ for the VESSEL12 dataset were achieved, outperforming works in the former and obtaining similar state-of-the-art results in the latter dataset, showing the capability in using deep learning approaches.

##### Abstract (translated by Google)
通常可以通过计算机断层扫描（CT）扫描分析癌症和其他病理疾病，如间质性肺病（ILDs）。为了解决这个问题，我们进行了分割的预处理步骤，以减少分析面积，分割肺部并去除不重要的区域。一般来说，开发复杂的方法来提取肺部区域，也使用手工特征提取器来增强分割。随着深度学习技术及其自动化特征学习的普及，我们提出了一种肺部分割方法，它使用完全卷积网络（FCN）和完全连接的条件随机场（CRF），并在许多最先进的分割工作中使用。为了开发一种通用的方法，研究了来自日内瓦大学医院（HUG）的公开数据集（HUG）和VESSEL12挑战，包括用于评估的许多健康和病理CT扫描。采用单独使用数据集的实验，其他数据集的训练模型和两个数据集的组合。骰子得分为HUG-ILD数据集的$ 98.67 \％\ pm0.94 \％$和VESSEL12数据集的$ 99.19 \％\ pm0.37 \％$，其性能优于前者，并获得类似的状态在后面的数据集中展示了使用深度学习方法的能力。

##### URL
[https://arxiv.org/abs/1804.10704](https://arxiv.org/abs/1804.10704)

##### PDF
[https://arxiv.org/pdf/1804.10704](https://arxiv.org/pdf/1804.10704)

