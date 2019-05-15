---
layout: post
title: "Efficient Ladder-style DenseNets for Semantic Segmentation of Large Images"
date: 2019-05-14 15:14:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification Prediction
author: Ivan Krešo, Josip Krapac, Siniša Šegvić
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress of deep image classification models has provided great potential to improve state-of-the-art performance in related computer vision tasks. However, the transition to semantic segmentation is hampered by strict memory limitations of contemporary GPUs. The extent of feature map caching required by convolutional backprop poses significant challenges even for moderately sized Pascal images, while requiring careful architectural considerations when the source resolution is in the megapixel range. To address these concerns, we propose a novel DenseNet-based ladder-style architecture which features high modelling power and a very lean upsampling datapath. We also propose to substantially reduce the extent of feature map caching by exploiting inherent spatial efficiency of the DenseNet feature extractor. The resulting models deliver high performance with fewer parameters than competitive approaches, and allow training at megapixel resolution on commodity hardware. The presented experimental results outperform the state-of-the-art in terms of prediction accuracy and execution speed on Cityscapes, Pascal VOC 2012, CamVid and ROB 2018 datasets. Source code will be released upon publication.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05661](https://arxiv.org/abs/1905.05661)

##### PDF
[https://arxiv.org/pdf/1905.05661](https://arxiv.org/pdf/1905.05661)

