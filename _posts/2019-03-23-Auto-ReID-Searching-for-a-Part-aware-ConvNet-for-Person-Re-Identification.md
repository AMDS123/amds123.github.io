---
layout: post
title: "Auto-ReID: Searching for a Part-aware ConvNet for Person Re-Identification"
date: 2019-03-23 07:26:50
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Classification
author: Ruijie Quan, Xuanyi Dong, Yu Wu, Linchao Zhu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Prevailing deep convolutional neural networks (CNNs) for person re-IDentification (reID) are usually built upon the ResNet or VGG backbones, which were originally designed for classification. Because reID has certain differences from classification, the architecture should be modified accordingly. We propose to search for a CNN architecture that is specifically suitable for the reID task. There are three main problems. First, body structural information plays an important role in reID but is not encoded in backbones. Part-based reID models incorporate structure information at the tail of a CNN. Performance relies heavily on human experts and the models are backbone-dependent, requiring extensive human effort when a different backbone is used. Second, Neural Architecture Search (NAS) automates the process of architecture design without human effort, but no existing NAS methods incorporate the structure information of input images. Third, reID is essentially a retrieval task but current NAS algorithms are merely designed for classification. To solve these problems, we propose a retrieval-based search algorithm over a specifically designed reID search space, named Auto-ReID. Our Auto-ReID enables the automated approach to find an efficient and effective CNN architecture that is specifically suitable for reID. Extensive experiments indicate that the searched architecture achieves state-of-the-art performance while requiring less than about 50% parameters and 53% FLOPs compared to others.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09776](http://arxiv.org/abs/1903.09776)

##### PDF
[http://arxiv.org/pdf/1903.09776](http://arxiv.org/pdf/1903.09776)

