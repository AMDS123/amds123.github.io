---
layout: post
title: "Classification and Disease Localization in Histopathology Using Only Global Labels: A Weakly-Supervised Approach"
date: 2018-02-01 15:21:14
categories: arXiv_CV
tags: arXiv_CV Review Object_Detection Segmentation Weakly_Supervised Embedding CNN Semantic_Segmentation Classification Deep_Learning Detection
author: Pierre Courtiol, Eric W. Tramel, Marc Sanselme, Gilles Wainrib
mathjax: true
---

* content
{:toc}

##### Abstract
Analysis of histopathology slides is a critical step for many diagnoses, and in particular in oncology where it defines the gold standard. In the case of digital histopathological analysis, highly trained pathologists must review vast whole-slide-images of extreme digital resolution ($100,000^2$ pixels) across multiple zoom levels in order to locate abnormal regions of cells, or in some cases single cells, out of millions. The application of deep learning to this problem is hampered not only by small sample sizes, as typical datasets contain only a few hundred samples, but also by the generation of ground-truth localized annotations for training interpretable classification and segmentation models. We propose a method for disease localization in the context of weakly supervised learning, where only image-level labels are available during training. Even without pixel-level annotations, we are able to demonstrate performance comparable with models trained with strong annotations on the Camelyon-16 lymph node metastases detection challenge. We accomplish this through the use of pre-trained deep convolutional networks, feature embedding, as well as learning via top instances and negative evidence, a multiple instance learning technique from the field of semantic segmentation and object detection.

##### Abstract (translated by Google)
对组织病理学的幻灯片进行分析是许多诊断的关键步骤，特别是在确定黄金标准的肿瘤学领域。在数字组织病理学分析的情况下，经过高度训练的病理学家必须在多个缩放级别上查看极端数字分辨率（$ 100,000 ^ 2 $像素）的巨大整幅幻灯片图像，以便定位细胞的异常区域，或者在某些情况下定位单个细胞，数以百万计深度学习在这个问题上的应用不仅受到小样本的阻碍，因为典型的数据集只包含几百个样本，而且还通过生成用于训练可解释分类和分割模型的地面真实本地化注释。我们提出了一种弱监督学习的疾病定位方法，在训练期间只有图像级标签可用。即使没有像素级别的注释，我们也能够证明性能可与Camelyon-16淋巴结转移检测挑战中强大的注释训练的模型相媲美。我们通过使用预先训练的深度卷积网络，特征嵌入，以及通过顶级实例和负面证据进行学习，从语义分割和对象检测领域实现多实例学习技术。

##### URL
[https://arxiv.org/abs/1802.02212](https://arxiv.org/abs/1802.02212)

##### PDF
[https://arxiv.org/pdf/1802.02212](https://arxiv.org/pdf/1802.02212)

