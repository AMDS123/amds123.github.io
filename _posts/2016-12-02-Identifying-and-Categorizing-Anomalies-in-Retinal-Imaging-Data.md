---
layout: post
title: "Identifying and Categorizing Anomalies in Retinal Imaging Data"
date: 2016-12-02 14:05:49
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Embedding CNN Classification Detection
author: Philipp Seeböck, Sebastian Waldstein, Sophie Klimscha, Bianca S. Gerendas, René Donner, Thomas Schlegl, Ursula Schmidt-Erfurth, Georg Langs
mathjax: true
---

* content
{:toc}

##### Abstract
The identification and quantification of markers in medical images is critical for diagnosis, prognosis and management of patients in clinical practice. Supervised- or weakly supervised training enables the detection of findings that are known a priori. It does not scale well, and a priori definition limits the vocabulary of markers to known entities reducing the accuracy of diagnosis and prognosis. Here, we propose the identification of anomalies in large-scale medical imaging data using healthy examples as a reference. We detect and categorize candidates for anomaly findings untypical for the observed data. A deep convolutional autoencoder is trained on healthy retinal images. The learned model generates a new feature representation, and the distribution of healthy retinal patches is estimated by a one-class support vector machine. Results demonstrate that we can identify pathologic regions in images without using expert annotations. A subsequent clustering categorizes findings into clinically meaningful classes. In addition the learned features outperform standard embedding approaches in a classification task.

##### Abstract (translated by Google)
医学图像中标志物的鉴定和定量对于临床实践中患者的诊断，预后和治疗至关重要。有监督或弱监督的训练使得能够检测先验已知的发现。它不能很好地扩展，先验定义将标记的词汇限制在已知的实体中，降低了诊断和预后的准确性。在这里，我们提出使用健康的例子来识别大规模医学影像数据中的异常现象。我们检测和分类候选人的异常结果观察数据不典型。深卷积自动编码器在健康的视网膜图像上进行训练。学习模型生成一个新的特征表示，健康的视网膜补丁的分布是由一个一类支持向量机估计。结果表明我们可以在不使用专家注释的情况下识别图像中的病理区域。随后的聚类将发现分类为具有临床意义的类别。此外，学习功能在分类任务中优于标准嵌入方法。

##### URL
[https://arxiv.org/abs/1612.00686](https://arxiv.org/abs/1612.00686)

##### PDF
[https://arxiv.org/pdf/1612.00686](https://arxiv.org/pdf/1612.00686)

