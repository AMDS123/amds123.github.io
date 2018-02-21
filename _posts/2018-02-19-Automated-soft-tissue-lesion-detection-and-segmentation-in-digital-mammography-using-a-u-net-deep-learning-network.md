---
layout: post
title: "Automated soft tissue lesion detection and segmentation in digital mammography using a u-net deep learning network"
date: 2018-02-19 21:39:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning Detection
author: Timothy de Moor, Alejandro Rodriguez-Ruiz, Ritse Mann, Jonas Teuwen
mathjax: true
---

* content
{:toc}

##### Abstract
Computer-aided detection or decision support systems aim to improve breast cancer screening programs by helping radiologists to evaluate digital mammography (DM) exams. Commonly such methods proceed in two steps: selection of candidate regions for malignancy, and later classification as either malignant or not. In this study, we present a candidate detection method based on deep learning to automatically detect and additionally segment soft tissue lesions in DM. A database of DM exams (mostly bilateral and two views) was collected from our institutional archive. In total, 7196 DM exams (28294 DM images) acquired with systems from three different vendors (General Electric, Siemens, Hologic) were collected, of which 2883 contained malignant lesions verified with histopathology. Data was randomly split on an exam level into training (50\%), validation (10\%) and testing (40\%) of deep neural network with u-net architecture. The u-net classifies the image but also provides lesion segmentation. Free receiver operating characteristic (FROC) analysis was used to evaluate the model, on an image and on an exam level. On an image level, a maximum sensitivity of 0.94 at 7.93 false positives (FP) per image was achieved. Similarly, per exam a maximum sensitivity of 0.98 at 7.81 FP per image was achieved. In conclusion, the method could be used as a candidate selection model with high accuracy and with the additional information of lesion segmentation.

##### Abstract (translated by Google)
计算机辅助检测或决策支持系统旨在通过帮助放射科医师评估数字乳房X光检查（DM）检查来改善乳腺癌筛查计划。通常这样的方法分两步进行：选择恶性肿瘤的候选区域，然后分类为恶性或不恶性。在这项研究中，我们提出了一种基于深度学习的候选检测方法，可以自动检测和附加分割DM中的软组织病变。我们的机构档案收集了DM考试数据库（主要是双边和两个视图）。总共收集了来自三个不同供应商（通用电气，西门子，Hologic）的系统获取的7196个DM检查（28294个DM影像），其中2883个包含经组织病理学验证的恶性病变。数据在考试水平上随机分为深度神经网络训练（50％），验证（10％）和测试（40％）。 u-net将图像分类，但也提供病灶分割。使用免费接收器操作特性（FROC）分析来评估模型，在图像上和考试水平上。在图像层面上，每幅图像的7.93误报（FP）的最大灵敏度为0.94。类似地，每次检查获得7.81FP /图像的最大灵敏度0.98。总之，该方法可以用作高精度的候选选择模型，并具有附加的病灶分割信息。

##### URL
[http://arxiv.org/abs/1802.06865](http://arxiv.org/abs/1802.06865)

##### PDF
[http://arxiv.org/pdf/1802.06865](http://arxiv.org/pdf/1802.06865)

