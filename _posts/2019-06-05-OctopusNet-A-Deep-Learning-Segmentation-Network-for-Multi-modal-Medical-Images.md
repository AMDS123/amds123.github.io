---
layout: post
title: "OctopusNet: A Deep Learning Segmentation Network for Multi-modal Medical Images"
date: 2019-06-05 13:47:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yu Chen, Yuexiang Li, Jiawei Chen, Yefeng Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models, such as the fully convolutional network (FCN), have been widely used in 3D biomedical segmentation and achieved state-of-the-art performance. Multiple modalities are often used for disease diagnosis and quantification. Two approaches are widely used in the literature to fuse multiple modalities in the segmentation networks: early-fusion (which stacks multiple modalities as different input channels) and late-fusion (which fuses the segmentation results from different modalities at the very end). These fusion methods easily suffer from the cross-modal interference caused by the input modalities which have wide variations. To address the problem, we propose a novel deep learning architecture, namely OctopusNet, to better leverage and fuse the information contained in multi-modalities. The proposed framework employs a separate encoder for each modality for feature extraction and exploits a hyper-fusion decoder to fuse the extracted features while avoiding feature explosion. We evaluate the proposed OctopusNet on two publicly available datasets, i.e. ISLES-2018 and MRBrainS-2013. The experimental results show that our framework outperforms the commonly-used feature fusion approaches and yields the state-of-the-art segmentation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02031](http://arxiv.org/abs/1906.02031)

##### PDF
[http://arxiv.org/pdf/1906.02031](http://arxiv.org/pdf/1906.02031)

