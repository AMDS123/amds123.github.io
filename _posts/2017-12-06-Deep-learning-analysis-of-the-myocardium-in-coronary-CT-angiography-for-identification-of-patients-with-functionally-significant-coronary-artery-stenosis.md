---
layout: post
title: "Deep learning analysis of the myocardium in coronary CT angiography for identification of patients with functionally significant coronary artery stenosis"
date: 2017-12-06 09:22:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Majd Zreik, Nikolas Lessmann, Robbert W. van Hamersvelt, Jelmer M. Wolterink, Michiel Voskuil, Max A. Viergever, Tim Leiner, Ivana I&#x161;gum
mathjax: true
---

* content
{:toc}

##### Abstract
In patients with coronary artery stenoses of intermediate severity, the functional significance needs to be determined. Fractional flow reserve (FFR) measurement, performed during invasive coronary angiography (ICA), is most often used in clinical practice. To reduce the number of ICA procedures, we present a method for automatic identification of patients with functionally significant coronary artery stenoses, employing deep learning analysis of the left ventricle (LV) myocardium in rest coronary CT angiography (CCTA). The study includes consecutively acquired CCTA scans of 166 patients with FFR measurements. To identify patients with a functionally significant coronary artery stenosis, analysis is performed in several stages. First, the LV myocardium is segmented using a multiscale convolutional neural network (CNN). To characterize the segmented LV myocardium, it is subsequently encoded using unsupervised convolutional autoencoder (CAE). Thereafter, patients are classified according to the presence of functionally significant stenosis using an SVM classifier based on the extracted and clustered encodings. Quantitative evaluation of LV myocardium segmentation in 20 images resulted in an average Dice coefficient of 0.91 and an average mean absolute distance between the segmented and reference LV boundaries of 0.7 mm. Classification of patients was evaluated in the remaining 126 CCTA scans in 50 10-fold cross-validation experiments and resulted in an area under the receiver operating characteristic curve of 0.74 +- 0.02. At sensitivity levels 0.60, 0.70 and 0.80, the corresponding specificity was 0.77, 0.71 and 0.59, respectively. The results demonstrate that automatic analysis of the LV myocardium in a single CCTA scan acquired at rest, without assessment of the anatomy of the coronary arteries, can be used to identify patients with functionally significant coronary artery stenosis.

##### Abstract (translated by Google)
在冠状动脉狭窄程度中等的患者中，功能意义需要确定。在有创性冠状动脉造影（ICA）期间进行的分数血流储备（FFR）测量是临床实践中最常使用的。为了减少ICA手术的次数，我们提出了一种自动识别患有功能重要的冠状动脉狭窄的患者的方法，在静息冠状动脉CT血管造影（CCTA）中对左心室（LV）心肌进行深度学习分析。该研究包括连续获得的166名FFR测量患者的CCTA扫描。为了鉴别具有功能重要的冠状动脉狭窄的患者，分析在几个阶段进行。首先，使用多尺度卷积神经网络（CNN）对LV心肌进行分割。为了表征分割的LV心肌，随后使用无监督卷积自动编码器（CAE）对其进行编码。此后，使用基于提取和成簇编码的SVM分类器，根据存在功能重要的狭窄来对患者进行分类。对20幅图像中LV心肌分割的定量评估导致平均Dice系数为0.91，并且分割的和参考LV边界之间的平均绝对距离为0.7mm。在剩余的126次CCTA扫描中评估患者的分类，在50次10倍交叉验证实验中得出，并且在接受者操作特征曲线下面积为0.74±0.02。在敏感性水平0.60,0.70和0.80时，相应的特异性分别为0.77,0.71和0.59。结果表明，在静息时获得的单个CCTA扫描中，在不评估冠状动脉的解剖结构的情况下自动分析LV心肌，可以用于识别具有功能重要的冠状动脉狭窄的患者。

##### URL
[http://arxiv.org/abs/1711.08917](http://arxiv.org/abs/1711.08917)

##### PDF
[http://arxiv.org/pdf/1711.08917](http://arxiv.org/pdf/1711.08917)

