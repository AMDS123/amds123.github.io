---
layout: post
title: "Lung Nodule Classification using Deep Local-Global Networks"
date: 2019-04-23 02:49:37
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning Classification
author: Mundher Al-Shabi, Boon Leong Lan, Wai Yee Chan, Kwan-Hoong Ng, Maxine Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Lung nodules have very diverse shapes and sizes, which makes classifying them as benign/malignant a challenging problem. In this paper, we propose a novel method to predict the malignancy of nodules that have the capability to analyze the shape and size of a nodule using a global feature extractor, as well as the density and structure of the nodule using a local feature extractor. Methods: We propose to use Residual Blocks with a 3x3 kernel size for local feature extraction, and Non-Local Blocks to extract the global features. The Non-Local Block has the ability to extract global features without using a huge number of parameters. The key idea behind the Non-Local Block is to apply matrix multiplications between features on the same feature maps. Results: We trained and validated the proposed method on the LIDC-IDRI dataset which contains 1,018 computed tomography (CT) scans. We followed a rigorous procedure for experimental setup namely, 10-fold cross-validation and ignored the nodules that had been annotated by less than 3 radiologists. The proposed method achieved state-of-the-art results with AUC=95.62%, while significantly outperforming other baseline methods. Conclusions: Our proposed Deep Local-Global network has the capability to accurately extract both local and global features. Our new method outperforms state-of-the-art architecture including Densenet and Resnet with transfer learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10126](http://arxiv.org/abs/1904.10126)

##### PDF
[http://arxiv.org/pdf/1904.10126](http://arxiv.org/pdf/1904.10126)

