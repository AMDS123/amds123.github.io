---
layout: post
title: "Fully Convolutional Network for Melanoma Diagnostics"
date: 2018-06-12 20:53:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Adon Phillips, Iris Teo, Jochen Lang
mathjax: true
---

* content
{:toc}

##### Abstract
This work seeks to determine how modern machine learning techniques may be applied to the previously unexplored topic of melanoma diagnostics using digital pathology. We curated a new dataset of 50 patient cases of cutaneous melanoma using digital pathology. We provide gold standard annotations for three tissue types (tumour, epidermis, and dermis) which are important for the prognostic measurements known as Breslow thickness and Clark level. Then, we devised a novel multi-stride fully convolutional network (FCN) architecture that outperformed other networks trained and evaluated using the same data according to standard metrics. Finally, we trained a model to detect and localize the target tissue types. When processing previously unseen cases, our model's output is qualitatively very similar to the gold standard. In addition to the standard metrics computed as a baseline for our approach, we asked three additional pathologists to measure the Breslow thickness on the network's output. Their responses were diagnostically equivalent to the ground truth measurements, and when removing cases where a measurement was not appropriate, inter-rater reliability (IRR) between the four pathologists was 75.0%. Given the qualitative and quantitative results, it is possible to overcome the discriminative challenges of the skin and tumour anatomy for segmentation using modern machine learning techniques, though more work is required to improve the network's performance on dermis segmentation. Further, we show that it is possible to achieve a level of accuracy required to manually perform the Breslow thickness measurement.

##### Abstract (translated by Google)
这项工作旨在确定现代机器学习技术如何应用​​于以前尚未开发的使用数字病理学的黑色素瘤诊断主题。我们利用数字病理学策划了一个新的50例皮肤黑色素瘤病例数据集。我们为三种组织类型（肿瘤，表皮和真皮）提供金标准注释，这对于称为Breslow厚度和Clark水平的预后测量是重要的。然后，我们设计了一种新颖的多步完全卷积网络（FCN）体系结构，其性能超过了根据标准度量使用相同数据进行训练和评估的其他网络。最后，我们训练了一个模型来检测和定位目标组织类型。在处理先前看不见的案例时，我们模型的输出在质量上与黄金标准非常相似。除了作为我们方法的基线计算的标准指标之外，我们还要求三名额外的病理学家测量网络输出的Breslow厚度。他们的反应在诊断上等同于基础真值测量，并且当除去测量不合适的情况时，四位病理学家之间的评分者间信度（IRR）为75.0％。鉴于定性和定量结果，尽管需要更多工作来改善网络在真皮分割上的表现，但仍有可能通过使用现代机器学习技术来克服用于分割的皮肤和肿瘤解剖学的区别性挑战。此外，我们表明可以达到手动执行Breslow厚度测量所需的准确度水平。

##### URL
[http://arxiv.org/abs/1806.04765](http://arxiv.org/abs/1806.04765)

##### PDF
[http://arxiv.org/pdf/1806.04765](http://arxiv.org/pdf/1806.04765)

