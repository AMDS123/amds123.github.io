---
layout: post
title: "An Ensemble Deep Learning Based Approach for Red Lesion Detection in Fundus Images"
date: 2017-10-12 19:44:36
categories: arXiv_CV
tags: arXiv_CV Knowledge Deep_Learning Detection
author: José Ignacio Orlando, Elena Prokofyeva, Mariana del Fresno, Matthew B. Blaschko
mathjax: true
---

* content
{:toc}

##### Abstract
Diabetic retinopathy is one of the leading causes of preventable blindness in the world. Its earliest sign are red lesions, a general term that groups both microaneurysms and hemorrhages. In daily clinical practice, these lesions are manually detected by physicians using fundus photographs. However, this task is tedious and time consuming, and requires an intensive effort due to the small size of the lesions and their lack of contrast. Computer-assisted diagnosis of DR based on red lesion detection is being actively explored due to its improvement effects both in clinicians consistency and accuracy. Several methods for detecting red lesions have been proposed in the literature, most of them based on characterizing lesion candidates using hand crafted features, and classifying them into true or false positive detections. Deep learning based approaches, by contrast, are scarce in this domain due to the high expense of annotating the lesions manually. In this paper we propose a novel method for red lesion detection based on combining both deep learned and domain knowledge. Features learned by a CNN are augmented by incorporating hand crafted features. Such ensemble vector of descriptors is used afterwards to identify true lesion candidates using a Random Forest classifier. We empirically observed that combining both sources of information significantly improve results with respect to using each approach separately. Furthermore, our method reported the highest performance on a per-lesion basis on DIARETDB1 and e-ophtha, and for screening and need for referral on MESSIDOR compared to a second human expert. Results highlight the fact that integrating manually engineered approaches with deep learned features is relevant to improve results when the networks are trained from lesion-level annotated data. An open source implementation of our system is publicly available online.

##### Abstract (translated by Google)
糖尿病性视网膜病变是世界上可预防失明的主要原因之一。其最早的征兆是红色病变，这是一个将微小动脉瘤和出血组合在一起的总称。在日常临床实践中，这些病变是由医生使用眼底照片手动检测的。然而，这个任务繁琐且费时，并且由于病变的小尺寸和缺乏对比度而需要大量的努力。基于红色病变检测的DR的计算机辅助诊断由于其对临床医生的一致性和准确性的改善效果而被积极地探索。在文献中已经提出了几种检测红色病变的方法，其中大多数是基于使用手工特征来表征病变候选者，并将其分类为真或假阳性检测。相比之下，基于深度学习的方法在这个领域是稀缺的，因为手动注释病变的高昂费用。本文提出了一种基于深度学习和领域知识相结合的红色病变检测新方法。由CNN学习的功能通过结合手工制作的功能得到增强。随后使用描述符的这种集合向量来使用随机森林分类器来识别真实病变候选者。我们经验地观察到，结合这两种信息来源显着改善了单独使用每种方法的结果。此外，我们的方法报告了DIARETDB1和e-ophtha在每个病变基础上的最高性能，以及与MESSIDOR相比，第二位人类专家筛选和需要转诊。结果强调，将手动工程方法与深度学习功能集成在一起，可以改善网络从病变级别注释数据训练时的结果。我们系统的开源实现可以在线公开获得。

##### URL
[https://arxiv.org/abs/1706.03008](https://arxiv.org/abs/1706.03008)

##### PDF
[https://arxiv.org/pdf/1706.03008](https://arxiv.org/pdf/1706.03008)

