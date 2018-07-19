---
layout: post
title: "Bag-of-Visual-Words for Signature-Based Multi-Script Document Retrieval"
date: 2018-07-18 04:29:20
categories: arXiv_CV
tags: arXiv_CV Classification
author: Ranju Mandal, Partha Pratim Roy, Umapada Pal, Michael Blumenstein
mathjax: true
---

* content
{:toc}

##### Abstract
An end-to-end architecture for multi-script document retrieval using handwritten signatures is proposed in this paper. The user supplies a query signature sample and the system exclusively returns a set of documents that contain the query signature. In the first stage, a component-wise classification technique separates the potential signature components from all other components. A bag-of-visual-words powered by SIFT descriptors in a patch-based framework is proposed to compute the features and a Support Vector Machine (SVM)-based classifier was used to separate signatures from the documents. In the second stage, features from the foreground (i.e. signature strokes) and the background spatial information (i.e. background loops, reservoirs etc.) were combined to characterize the signature object to match with the query signature. Finally, three distance measures were used to match a query signature with the signature present in target documents for retrieval. The `Tobacco' document database and an Indian script database containing 560 documents of Devanagari (Hindi) and Bangla scripts were used for the performance evaluation. The proposed system was also tested on noisy documents and promising results were obtained. A comparative study shows that the proposed method outperforms the state-of-the-art approaches.

##### Abstract (translated by Google)
本文提出了一种使用手写签名进行多脚本文档检索的端到端体系结构。用户提供查询签名样本，系统专门返回包含查询签名的一组文档。在第一阶段，组件分类技术将潜在的签名组件与所有其他组件分开。提出了基于补丁的框架中由SIFT描述符提供支持的视觉词袋来计算特征，并且基于支持向量机（SVM）的分类器用于将签名与文档分离。在第二阶段，组合来自前景的特征（即签名笔划）和背景空间信息（即背景循环，储存器等）以表征签名对象以与查询签名匹配。最后，使用三个距离度量来将查询签名与目标文档中存在的签名进行匹配以进行检索。 “烟草”文件数据库和印度脚本数据库包含560份梵文（印地语）和孟加拉文字文件，用于绩效评估。所提出的系统也在嘈杂的文件上进行了测试，并获得了有希望的结果。比较研究表明，所提出的方法优于最先进的方法。

##### URL
[https://arxiv.org/abs/1807.06772](https://arxiv.org/abs/1807.06772)

##### PDF
[https://arxiv.org/pdf/1807.06772](https://arxiv.org/pdf/1807.06772)

