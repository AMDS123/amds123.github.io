---
layout: post
title: "CNNs-based Acoustic Scene Classification using Multi-Spectrogram Fusion and Label Expansions"
date: 2018-09-05 14:34:08
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Weiping Zheng, Zhenyao Mo, Xiaotao Xing, Gansen Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Spectrograms have been widely used in Convolutional Neural Networks based schemes for acoustic scene classification, such as the STFT spectrogram and the MFCC spectrogram, etc. They have different time-frequency characteristics, contributing to their own advantages and disadvantages in recognizing acoustic scenes. In this letter, a novel multi-spectrogram fusion framework is proposed, making the spectrograms complement each other. In the framework, a single CNN architecture is applied onto multiple spectrograms for feature extraction. The deep features extracted from multiple spectrograms are then fused to discriminate the acoustic scenes. Moreover, motivated by the inter-class similarities in acoustic scene datasets, a label expansion method is further proposed in which super-class labels are constructed upon the original classes. On the help of the expanded labels, the CNN models are transformed into the multitask learning form to improve the acoustic scene classification by appending the auxiliary task of super-class classification. To verify the effectiveness of the proposed methods, intensive experiments have been performed on the DCASE2017 and the LITIS Rouen datasets. Experimental results show that the proposed method can achieve promising accuracies on both datasets. Specifically, accuracies of 0.9744, 0.8865 and 0.7778 are obtained for the LITIS Rouen dataset, the DCASE Development set and Evaluation set respectively.

##### Abstract (translated by Google)
频谱图已经广泛用于基于卷积神经网络的声学场景分类方案，例如STFT频谱图和MFCC频谱图等。它们具有不同的时频特性，有助于它们在识别声学场景中的优点和缺点。在这封信中，提出了一种新颖的多光谱图融合框架，使光谱图相互补充。在该框架中，将单个CNN架构应用于多个频谱图以进行特征提取。然后融合从多个谱图中提取的深度特征以区分声学场景。此外，在声学场景数据集中的类间相似性的推动下，进一步提出了一种标签扩展方法，其中在原始类上构造超类标签。在扩展标签的帮助下，将CNN模型转换为多任务学习形式，通过附加超类分类的辅助任务来改进声场分类。为了验证所提方法的有效性，已对DCASE2017和LITIS Rouen数据集进行了深入的实验。实验结果表明，该方法可以在两个数据集上实现有前途的精度。具体而言，LITIS Rouen数据集，DCASE开发集和评估集分别获得0.9744,0.8865和0.7778的准确度。

##### URL
[http://arxiv.org/abs/1809.01543](http://arxiv.org/abs/1809.01543)

##### PDF
[http://arxiv.org/pdf/1809.01543](http://arxiv.org/pdf/1809.01543)

