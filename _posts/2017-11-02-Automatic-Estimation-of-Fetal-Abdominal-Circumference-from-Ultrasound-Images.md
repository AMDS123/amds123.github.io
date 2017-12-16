---
layout: post
title: "Automatic Estimation of Fetal Abdominal Circumference from Ultrasound Images"
date: 2017-11-02 05:59:49
categories: arXiv_CV
tags: arXiv_CV CNN Classification Quantitative
author: Jaeseong Jang, Yejin Park, Bukweon Kim, Sung Min Lee, Ja-Young Kwon, Jin Keun Seo
mathjax: true
---

* content
{:toc}

##### Abstract
Ultrasound diagnosis is routinely used in obstetrics and gynecology for fetal biometry, and owing to its time-consuming process, there has been a great demand for automatic estimation. However, the automated analysis of ultrasound images is complicated because they are patient-specific, operator-dependent, and machine-specific. Among various types of fetal biometry, the accurate estimation of abdominal circumference (AC) is especially difficult to perform automatically because the abdomen has low contrast against surroundings, non-uniform contrast, and irregular shape compared to other parameters.We propose a method for the automatic estimation of the fetal AC from 2D ultrasound data through a specially designed convolutional neural network (CNN), which takes account of doctors' decision process, anatomical structure, and the characteristics of the ultrasound image. The proposed method uses CNN to classify ultrasound images (stomach bubble, amniotic fluid, and umbilical vein) and Hough transformation for measuring AC. We test the proposed method using clinical ultrasound data acquired from 56 pregnant women. Experimental results show that, with relatively small training samples, the proposed CNN provides sufficient classification results for AC estimation through the Hough transformation. The proposed method automatically estimates AC from ultrasound images. The method is quantitatively evaluated, and shows stable performance in most cases and even for ultrasound images deteriorated by shadowing artifacts. As a result of experiments for our acceptance check, the accuracies are 0.809 and 0.771 with the expert 1 and expert 2, respectively, while the accuracy between the two experts is 0.905. However, for cases of oversized fetus, when the amniotic fluid is not observed or the abdominal area is distorted, it could not correctly estimate AC.

##### Abstract (translated by Google)
超声波诊断通常用于妇产科用于胎儿生物测量，由于其耗时的过程，对自动估计的需求很大。然而，超声图像的自动分析是复杂的，因为它们是患者特定的，操作者依赖的和机器特定的。在各种类型的胎儿生物测量中，由于腹部与周围环境的对比度低，对比度不均匀，且形状不规则，所以对腹围（AC）的精确估计尤其难以自动执行。我们提出了一种通过特殊设计的卷积神经网络（CNN）从2D超声数据中自动估算胎儿AC，考虑到医生的决策过程，解剖结构和超声图像的特点。所提出的方法使用CNN对超声图像（胃泡，羊水和脐静脉）和Hough变换进行分类以用于测量AC。我们使用从56名孕妇获得的临床超声数据来测试所提出的方法。实验结果表明，在相对较小的训练样本情况下，提出的CNN算法通过Hough变换提供了充分的AC估计分类结果。所提出的方法自动估计来自超声图像的AC。该方法是定量评估，并显示在大多数情况下稳定的性能，甚至超声图像劣化的阴影伪影。通过我们验收的实验验证，专家1和专家2的准确度分别为0.809和0.771，而两位专家的准确率分别为0.905。但是，对于胎儿超大的情况，如果没有观察到羊水，或者腹部区域扭曲，则无法正确估计AC。

##### URL
[https://arxiv.org/abs/1702.02741](https://arxiv.org/abs/1702.02741)

##### PDF
[https://arxiv.org/pdf/1702.02741](https://arxiv.org/pdf/1702.02741)

