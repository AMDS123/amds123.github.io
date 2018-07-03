---
layout: post
title: "Confounding variables can degrade generalization performance of radiological deep learning models"
date: 2018-07-02 01:57:38
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: John R. Zech, Marcus A. Badgeley, Manway Liu, Anthony B. Costa, Joseph J. Titano, Eric K. Oermann
mathjax: true
---

* content
{:toc}

##### Abstract
Early results in using convolutional neural networks (CNNs) on x-rays to diagnose disease have been promising, but it has not yet been shown that models trained on x-rays from one hospital or one group of hospitals will work equally well at different hospitals. Before these tools are used for computer-aided diagnosis in real-world clinical settings, we must verify their ability to generalize across a variety of hospital systems. A cross-sectional design was used to train and evaluate pneumonia screening CNNs on 158,323 chest x-rays from NIH (n=112,120 from 30,805 patients), Mount Sinai (42,396 from 12,904 patients), and Indiana (n=3,807 from 3,683 patients). In 3 / 5 natural comparisons, performance on chest x-rays from outside hospitals was significantly lower than on held-out x-rays from the original hospital systems. CNNs were able to detect where an x-ray was acquired (hospital system, hospital department) with extremely high accuracy and calibrate predictions accordingly. The performance of CNNs in diagnosing diseases on x-rays may reflect not only their ability to identify disease-specific imaging findings on x-rays, but also their ability to exploit confounding information. Estimates of CNN performance based on test data from hospital systems used for model training may overstate their likely real-world performance.

##### Abstract (translated by Google)
在X射线上使用卷积神经网络（CNN）诊断疾病的早期结果一直很有希望，但尚未证明从一家医院或一组医院接受X射线训练的模型在不同的医院同样有效。在将这些工具用于实际临床环境中的计算机辅助诊断之前，我们必须验证其在各种医院系统中进行推广的能力。横断面设计用于训练和评估来自NIH（n = 112,120，来自30,805名患者），西奈山（来自12,904名患者的42,396名）和印第安纳州（来自3,683名患者，n = 3,807）的158,323例胸部X射线照射和评估肺炎CNN的肺炎。 。在3/5的自然比较中，来自外部医院的胸部X射线的性能显着低于来自原始医院系统的持续X射线。 CNN能够以极高的准确度检测X射线的获取位置（医​​院系统，医院部门）并相应地校准预测。 CNN在诊断X射线疾病方面的表现不仅可以反映他们识别X射线疾病特异性成像结果的能力，还可以反映他们利用混杂信息的能力。基于来自用于模型训练的医院系统的测试数据估计CNN性能可能夸大其可能的实际表现。

##### URL
[http://arxiv.org/abs/1807.00431](http://arxiv.org/abs/1807.00431)

##### PDF
[http://arxiv.org/pdf/1807.00431](http://arxiv.org/pdf/1807.00431)

