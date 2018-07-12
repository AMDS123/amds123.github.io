---
layout: post
title: "Data-Driven Segmentation of Post-mortem Iris Images"
date: 2018-07-11 14:21:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Recognition
author: Mateusz Trokielewicz, Adam Czajka
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for segmenting iris images obtained from the deceased subjects, by training a deep convolutional neural network (DCNN) designed for the purpose of semantic segmentation. Post-mortem iris recognition has recently emerged as an alternative, or additional, method useful in forensic analysis. At the same time it poses many new challenges from the technological standpoint, one of them being the image segmentation stage, which has proven difficult to be reliably executed by conventional iris recognition methods. Our approach is based on the SegNet architecture, fine-tuned with 1,300 manually segmented post-mortem iris images taken from the Warsaw-BioBase-Post-Mortem-Iris v1.0 database. The experiments presented in this paper show that this data-driven solution is able to learn specific deformations present in post-mortem samples, which are missing from alive irises, and offers a considerable improvement over the state-of-the-art, conventional segmentation algorithm (OSIRIS): the Intersection over Union (IoU) metric was improved from 73.6% (for OSIRIS) to 83% (for DCNN-based presented in this paper) averaged over subject-disjoint, multiple splits of the data into train and test subsets. This paper offers the first known to us method of automatic processing of post-mortem iris images. We offer source codes with the trained DCNN that perform end-to-end segmentation of post-mortem iris images, as described in this paper. Also, we offer binary masks corresponding to manual segmentation of samples from Warsaw-BioBase-Post-Mortem-Iris v1.0 database to facilitate development of alternative methods for post-mortem iris segmentation.

##### Abstract (translated by Google)
本文提出了一种通过训练设计用于语义分割的深度卷积神经网络（DCNN）来分割从已故受试者获得的虹膜图像的方法。验尸虹膜识别最近已成为法医分析中可用的替代方法或其他方法。同时，从技术角度来看，它带来了许多新的挑战，其中之一是图像分割阶段，已经证明难以通过传统的虹膜识别方法可靠地执行。我们的方法基于SegNet架构，使用华沙 -  BioBase-Post-Mortem-Iris v1.0数据库中的1,300个手动分段的验尸虹膜图像进行微调。本文提出的实验表明，这种数据驱动的解决方案能够学习死活样品中存在的特定变形，这些变形在活虹膜中缺失，并且相对于现有技术的传统分割提供了相当大的改进。算法（OSIRIS）：联合交叉（IoU）度量标准从73.6％（对于OSIRIS）提高到83％（对于本文中提出的基于DCNN的平均值）对主题不相交，数据多次拆分为训练和测试的平均值子集。本文提供了我们第一个自动处理验尸虹膜图像的方法。如本文所述，我们提供具有经过训练的DCNN的源代码，该DCNN执行死后虹膜图像的端到端分割。此外，我们提供二元掩模，对应于Warsaw-BioBase-Post-Mortem-Iris v1.0数据库中样本的手动分割，以促进用于验尸后虹膜分割的替代方法的开发。

##### URL
[http://arxiv.org/abs/1807.04154](http://arxiv.org/abs/1807.04154)

##### PDF
[http://arxiv.org/pdf/1807.04154](http://arxiv.org/pdf/1807.04154)

