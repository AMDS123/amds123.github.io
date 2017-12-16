---
layout: post
title: "Automatic labeling of molecular biomarkers of whole slide immunohistochemistry images using fully convolutional networks"
date: 2016-12-30 08:27:04
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Fahime Sheikhzadeh, Martial Guillaud, Rabab K. Ward
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of quantifying biomarkers in multi-stained tissues, based on color and spatial information. A deep learning based method that can automatically localize and quantify the cells expressing biomarker(s) in a whole slide image is proposed. The deep learning network is a fully convolutional network (FCN) whose input is the true RGB color image of a tissue and output is a map of the different biomarkers. The FCN relies on a convolutional neural network (CNN) that classifies each cell separately according to the biomarker it expresses. In this study, images of immunohistochemistry (IHC) stained slides were collected and used. More than 4,500 RGB images of cells were manually labeled based on the expressing biomarkers. The labeled cell images were used to train the CNN (obtaining an accuracy of 92% in a test set). The trained CNN is then extended to an FCN that generates a map of all biomarkers in the whole slide image acquired by the scanner (instead of classifying every cell image). To evaluate our method, we manually labeled all nuclei expressing different biomarkers in two whole slide images and used theses as the ground truth. Our proposed method for immunohistochemical analysis compares well with the manual labeling by humans (average F-score of 0.96).

##### Abstract (translated by Google)
本文介绍了基于颜色和空间信息量化多染色组织中生物标志物的问题。提出了一种基于深度学习的方法，可以自动定位和定量整个幻灯片图像中表达生物标志物的细胞。深度学习网络是完全卷积网络（FCN），其输入是组织的真实RGB彩色图像，输出是不同生物标志物的图谱。 FCN依靠卷积神经网络（CNN），根据其表达的生物标志物分别分类每个细胞。在这项研究中，收集和使用免疫组织化学（IHC）染色的幻灯片的图像。基于表达的生物标志物手动标记了4,500个以上的RGB细胞图像。标记的细胞图像被用来训练CNN（在测试集中获得92％的准确度）。然后将训练的CNN扩展到FCN，该FCN生成由扫描仪获取的整个载玻片图像中的所有生物标志物的图谱（而不是对每个细胞图像进行分类）。为了评估我们的方法，我们在两幅完整的载玻片图像中手动标记表达不同生物标志物的所有细胞核，并将其用作基础事实。我们建议的免疫组织化学分析方法与人工手工标记（平均F值为0.96）相比较。

##### URL
[https://arxiv.org/abs/1612.09420](https://arxiv.org/abs/1612.09420)

##### PDF
[https://arxiv.org/pdf/1612.09420](https://arxiv.org/pdf/1612.09420)

