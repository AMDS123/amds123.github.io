---
layout: post
title: "Holistic Interstitial Lung Disease Detection using Deep Convolutional Neural Networks: Multi-label Learning and Unordered Pooling"
date: 2017-01-19 21:52:21
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Mingchen Gao, Ziyue Xu, Le Lu, Adam P. Harrison, Ronald M. Summers, Daniel J. Mollura
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately predicting and detecting interstitial lung disease (ILD) patterns given any computed tomography (CT) slice without any pre-processing prerequisites, such as manually delineated regions of interest (ROIs), is a clinically desirable, yet challenging goal. The majority of existing work relies on manually-provided ILD ROIs to extract sampled 2D image patches from CT slices and, from there, performs patch-based ILD categorization. Acquiring manual ROIs is labor intensive and serves as a bottleneck towards fully-automated CT imaging ILD screening over large-scale populations. Furthermore, despite the considerable high frequency of more than one ILD pattern on a single CT slice, previous works are only designed to detect one ILD pattern per slice or patch. To tackle these two critical challenges, we present multi-label deep convolutional neural networks (CNNs) for detecting ILDs from holistic CT slices (instead of ROIs or sub-images). Conventional single-labeled CNN models can be augmented to cope with the possible presence of multiple ILD pattern labels, via 1) continuous-valued deep regression based robust norm loss functions or 2) a categorical objective as the sum of element-wise binary logistic losses. Our methods are evaluated and validated using a publicly available database of 658 patient CT scans under five-fold cross-validation, achieving promising performance on detecting four major ILD patterns: Ground Glass, Reticular, Honeycomb, and Emphysema. We also investigate the effectiveness of a CNN activation-based deep-feature encoding scheme using Fisher vector encoding, which treats ILD detection as spatially-unordered deep texture classification.

##### Abstract (translated by Google)
给定任何计算机断层扫描（CT）切片，没有任何预处理先决条件（如手动划定的感兴趣区域（ROI）），准确地预测和检测间质性肺疾病（ILD）模式是一个临床上可取的，但具有挑战性的目标。现有的大部分工作依靠手动提供的ILD ROI从CT切片中提取采样的2D图像补丁，并从那里执行基于补丁的ILD分类。获取手动投资回报率是一项劳动密集型工作，并成为在大规模人群中实现全自动CT成像ILD筛查的瓶颈。此外，尽管单个CT切片上具有多于一个ILD图案的高频率，但以前的作品仅被设计用于检测每个切片或贴片的一个ILD图案。为了解决这两个关键的挑战，我们提出了多标签深度卷积神经网络（CNN）来检测来自整体CT切片（而不是ROI或子图像）的ILD。传统的单标记CNN模型可以通过1）基于连续值深度回归的鲁棒模损失函数或2）作为元素二元逻辑损失的总和的分类目标来增强以处理可能存在多个ILD模式标签。我们的方法评估和验证使用公开可用的数据库中的658例患者的CT扫描五倍交叉验证，实现有前途的表现检测四个主要的ILD模式：磨玻璃，网状，蜂窝状和肺气肿。我们还调查了基于CNN激活的深度特征编码方案的有效性，使用Fisher矢量编码，将ILD检测作为空间无序的深度纹理分类。

##### URL
[https://arxiv.org/abs/1701.05616](https://arxiv.org/abs/1701.05616)

##### PDF
[https://arxiv.org/pdf/1701.05616](https://arxiv.org/pdf/1701.05616)

