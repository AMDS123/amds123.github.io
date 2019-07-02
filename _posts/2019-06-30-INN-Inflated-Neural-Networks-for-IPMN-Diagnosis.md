---
layout: post
title: "INN: Inflated Neural Networks for IPMN Diagnosis"
date: 2019-06-30 19:24:41
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Rodney LaLonde, Irene Tanner, Katerina Nikiforaki, Georgios Z. Papadakis, Pujan Kandel, Candice W. Bolan, Michael B. Wallace, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Intraductal papillary mucinous neoplasm (IPMN) is a precursor to pancreatic ductal adenocarcinoma. While over half of patients are diagnosed with pancreatic cancer at a distant stage, patients who are diagnosed early enjoy a much higher 5-year survival rate of $34\%$ compared to $3\%$ in the former; hence, early diagnosis is key. Unique challenges in the medical imaging domain such as extremely limited annotated data sets and typically large 3D volumetric data have made it difficult for deep learning to secure a strong foothold. In this work, we construct two novel "inflated" deep network architectures, $\textit{InceptINN}$ and $\textit{DenseINN}$, for the task of diagnosing IPMN from multisequence (T1 and T2) MRI. These networks inflate their 2D layers to 3D and bootstrap weights from their 2D counterparts (Inceptionv3 and DenseNet121 respectively) trained on ImageNet to the new 3D kernels. We also extend the inflation process by further expanding the pre-trained kernels to handle any number of input modalities and different fusion strategies. This is one of the first studies to train an end-to-end deep network on multisequence MRI for IPMN diagnosis, and shows that our proposed novel inflated network architectures are able to handle the extremely limited training data (139 MRI scans), while providing an absolute improvement of $8.76\%$ in accuracy for diagnosing IPMN over the current state-of-the-art. Code is publicly available at https://github.com/lalonderodney/INN-Inflated-Neural-Nets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00437](http://arxiv.org/abs/1907.00437)

##### PDF
[http://arxiv.org/pdf/1907.00437](http://arxiv.org/pdf/1907.00437)

