---
layout: post
title: "Feature Extraction for Machine Learning Based Crackle Detection in Lung Sounds from a Health Survey"
date: 2017-12-23 22:25:06
categories: arXiv_SD
tags: arXiv_SD Survey Detection
author: Morten Gr&#xf8;nnesby, Juan Carlos Aviles Solis, Einar Holsb&#xf8;, Hasse Melbye, Lars Ailo Bongo
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, many innovative solutions for recording and viewing sounds from a stethoscope have become available. However, to fully utilize such devices, there is a need for an automated approach for detecting abnormal lung sounds, which is better than the existing methods that typically have been developed and evaluated using a small and non-diverse dataset. 
 We propose a machine learning based approach for detecting crackles in lung sounds recorded using a stethoscope in a large health survey. Our method is trained and evaluated using 209 files with crackles classified by expert listeners. Our analysis pipeline is based on features extracted from small windows in audio files. We evaluated several feature extraction methods and classifiers. We evaluated the pipeline using a training set of 175 crackle windows and 208 normal windows. We did 100 cycles of cross validation where we shuffled training sets between cycles. For all the division between training and evaluation was 70%-30%. 
 We found and evaluated a 5-dimenstional vector with four features from the time domain and one from the spectrum domain. We evaluated several classifiers and found SVM with a Radial Basis Function Kernel to perform best. Our approach had a precision of 86% and recall of 84% for classifying a crackle in a window, which is more accurate than found in studies of health personnel. The low-dimensional feature vector makes the SVM very fast. The model can be trained on a regular computer in 1.44 seconds, and 319 crackles can be classified in 1.08 seconds. 
 Our approach detects and visualizes individual crackles in recorded audio files. It is accurate, fast, and has low resource requirements. It can be used to train health personnel or as part of a smartphone application for Bluetooth stethoscopes.

##### Abstract (translated by Google)
近年来，许多用于从听诊器记录和观看声音的创新解决方案已经变得可用。然而，为了充分利用这些装置，需要一种用于检测肺部异常声音的自动化方法，这比现有方法更好，所述方法通常是使用小而无差别的数据集来开发和评估的。
 我们提出了一个基于机器学习的方法，用于检测大型健康调查中使用听诊器记录的肺音爆音。我们的方法是训练和评估使用209专家听众分类的裂纹文件。我们的分析管道基于从音频文件中的小窗口提取的特征。我们评估了几个特征提取方法和分类器。我们使用175个裂缝窗口和208个正常窗口的训练集对管道进行了评估。我们进行了100次循环验证，我们在循环之间对训练集进行了混洗。所有的培训和评估之间的分工是70％-30％。
 我们发现并评估了一个具有来自时域和来自频域的四个特征的五维矢量。我们评估了几个分类器，并发现了一个径向基函数内核的支持向量机执行得最好。我们的方法有86％的精确度和84％的回忆窗口分类裂纹，这比在卫生人员的研究中发现更准确。低维特征向量使得SVM非常快速。该模型可以在1.44秒内在普通计算机上训练，并且可以在1.08秒内分类319次。
 我们的方法检测和可视化录制的音频文件中的单个裂纹。准确，快速，资源要求低。它可以用来培训卫生人员或作为蓝牙听诊器智能手机应用程序的一部分。

##### URL
[http://arxiv.org/abs/1706.00005](http://arxiv.org/abs/1706.00005)

##### PDF
[http://arxiv.org/pdf/1706.00005](http://arxiv.org/pdf/1706.00005)

