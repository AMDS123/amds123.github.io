---
layout: post
title: "Deep Convolutional Neural Networks for Computer-Aided Detection: CNN Architectures, Dataset Characteristics and Transfer Learning"
date: 2016-02-10 15:33:32
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Transfer_Learning Classification Detection Recognition
author: Hoo-Chang Shin, Holger R. Roth, Mingchen Gao, Le Lu, Ziyue Xu, Isabella Nogues, Jianhua Yao, Daniel Mollura, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Remarkable progress has been made in image recognition, primarily due to the availability of large-scale annotated datasets and the revival of deep CNN. CNNs enable learning data-driven, highly representative, layered hierarchical image features from sufficient training data. However, obtaining datasets as comprehensively annotated as ImageNet in the medical imaging domain remains a challenge. There are currently three major techniques that successfully employ CNNs to medical image classification: training the CNN from scratch, using off-the-shelf pre-trained CNN features, and conducting unsupervised CNN pre-training with supervised fine-tuning. Another effective method is transfer learning, i.e., fine-tuning CNN models pre-trained from natural image dataset to medical image tasks. In this paper, we exploit three important, but previously understudied factors of employing deep convolutional neural networks to computer-aided detection problems. We first explore and evaluate different CNN architectures. The studied models contain 5 thousand to 160 million parameters, and vary in numbers of layers. We then evaluate the influence of dataset scale and spatial image context on performance. Finally, we examine when and why transfer learning from pre-trained ImageNet (via fine-tuning) can be useful. We study two specific computer-aided detection (CADe) problems, namely thoraco-abdominal lymph node (LN) detection and interstitial lung disease (ILD) classification. We achieve the state-of-the-art performance on the mediastinal LN detection, with 85% sensitivity at 3 false positive per patient, and report the first five-fold cross-validation classification results on predicting axial CT slices with ILD categories. Our extensive empirical evaluation, CNN model analysis and valuable insights can be extended to the design of high performance CAD systems for other medical imaging tasks.

##### Abstract (translated by Google)
图像识别技术取得了显着的进步，主要是由于大规模注释数据集的可用性以及深度CNN的复兴。 CNN使得能够从充足的训练数据中学习数据驱动的，高度代表性的，分层的分层图像特征。然而，在医学成像领域获得全面注释为ImageNet的数据集仍然是一个挑战。目前有三种主要技术成功地将CNN用于医学图像分类：从零开始训练CNN，使用现成的预先训练的CNN特征，并且通过监督微调进行无监督的CNN预训练。另一种有效的方法是转移学习，即对从自然图像数据集预先训练的CNN模型进行微调，以适应医学图像任务。在本文中，我们利用三个重要的，但以前被忽略的因素，深度卷积神经网络应用于计算机辅助检测问题。我们首先探索和评估不同的CNN体​​系结构。所研究的模型包含5千至一亿六千万个参数，并且层数不同。然后我们评估数据集规模和空间图像上下文对性能的影响。最后，我们研究何时以及为什么从预先训练的ImageNet（通过微调）转移学习是有用的。我们研究两种特定的计算机辅助检测（CADe）问题，即胸腹腔淋巴结（LN）检测和间质性肺病（ILD）分类。我们在纵隔淋巴结检测方面取得了最先进的表现，在每例患者3例假阳性的情况下，灵敏度达到85％，并且报告了使用ILD类别预测轴位CT切片的前5个交叉验证分类结果。我们广泛的实证评估，CNN模型分析和宝贵的见解可以扩展到其他医疗成像任务的高性能CAD系统的设计。

##### URL
[https://arxiv.org/abs/1602.03409](https://arxiv.org/abs/1602.03409)

##### PDF
[https://arxiv.org/pdf/1602.03409](https://arxiv.org/pdf/1602.03409)

