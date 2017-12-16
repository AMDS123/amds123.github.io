---
layout: post
title: "Yet Another ADNI Machine Learning Paper? Paving The Way Towards Fully-reproducible Research on Classification of Alzheimer's Disease"
date: 2017-09-21 11:37:01
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jorge Samper-González, Ninon Burgos, Sabrina Fontanella, Hugo Bertin, Marie-Odile Habert, Stanley Durrleman, Theodoros Evgeniou, Olivier Colliot
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, the number of papers on Alzheimer's disease classification has increased dramatically, generating interesting methodological ideas on the use machine learning and feature extraction methods. However, practical impact is much more limited and, eventually, one could not tell which of these approaches are the most efficient. While over 90\% of these works make use of ADNI an objective comparison between approaches is impossible due to variations in the subjects included, image pre-processing, performance metrics and cross-validation procedures. In this paper, we propose a framework for reproducible classification experiments using multimodal MRI and PET data from ADNI. The core components are: 1) code to automatically convert the full ADNI database into BIDS format; 2) a modular architecture based on Nipype in order to easily plug-in different classification and feature extraction tools; 3) feature extraction pipelines for MRI and PET data; 4) baseline classification approaches for unimodal and multimodal features. This provides a flexible framework for benchmarking different feature extraction and classification tools in a reproducible manner. We demonstrate its use on all (1519) baseline T1 MR images and all (1102) baseline FDG PET images from ADNI 1, GO and 2 with SPM-based feature extraction pipelines and three different classification techniques (linear SVM, anatomically regularized SVM and multiple kernel learning SVM). The highest accuracies achieved were: 91% for AD vs CN, 83% for MCIc vs CN, 75% for MCIc vs MCInc, 94% for AD-A$\beta$+ vs CN-A$\beta$- and 72% for MCIc-A$\beta$+ vs MCInc-A$\beta$+. The code is publicly available at this https URL (depends on the Clinica software platform, publicly available at this http URL).

##### Abstract (translated by Google)
近年来，关于阿尔茨海默病分类的论文数量急剧增加，对使用机器学习和特征提取方法产生了有趣的方法论思想。然而，实际的影响更为有限，最终无法分辨出哪种方法是最有效的。尽管这些作品中超过90％使用了ADNI，但是由于所包含主题的变化，图像预处理，性能指标和交叉验证程序等原因，不可能在两种方法之间进行客观的比较。在本文中，我们提出了使用ADNI的多模态MRI和PET数据进行重复性分类实验的框架。核心组件是：1）自动将完整的ADNI数据库转换为BIDS格式的代码; 2）基于Nipype的模块化架构，以便轻松插入不同的分类和特征提取工具; 3）用于MRI和PET数据的特征提取管线; 4）单峰和多峰特征的基线分类方法。这为以不同的特征提取和分类工具以可重现的方式进行基准测试提供了一个灵活的框架。我们在所有（1519）基线T1 MR图像和来自ADNI 1，GO和2的基于SPM的特征提取管线和三种不同的分类技术（线性SVM，解剖学正则化的SVM和多个内核学习SVM）。达到最高的准确度是：AD对CN 91％，MCIc对CN CNP 83％，MCIc对MCInc 75％，AD-A $ \ beta $ +对CN-A $ \ beta $ 94％，72％对于MCIc-A $ \ beta $ + +对MCInc-A $ \ beta $ +。该代码可在此https URL公开获得（取决于Clinica软件平台，可通过此http URL公开获得）。

##### URL
[https://arxiv.org/abs/1709.07267](https://arxiv.org/abs/1709.07267)

##### PDF
[https://arxiv.org/pdf/1709.07267](https://arxiv.org/pdf/1709.07267)

