---
layout: post
title: "Soft labeling by Distilling Anatomical knowledge for Improved MS Lesion Segmentation"
date: 2019-01-26 18:52:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Detection
author: Eytan Kats, Jacob Goldberger, Hayit Greenspan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores the use of a soft ground-truth mask ("soft mask'') to train a Fully Convolutional Neural Network (FCNN) for segmentation of Multiple Sclerosis (MS) lesions. Detection and segmentation of MS lesions is a complex task largely due to the extreme unbalanced data, with very small number of lesion pixels that can be used for training. Utilizing the anatomical knowledge that the lesion surrounding pixels may also include some lesion level information, we suggest to increase the data set of the lesion class with neighboring pixel data - with a reduced confidence weight. A soft mask is constructed by morphological dilation of the binary segmentation mask provided by a given expert, where expert-marked voxels receive label 1 and voxels of the dilated region are assigned a soft label. In the methodology proposed, the FCNN is trained using the soft mask. On the ISBI 2015 challenge dataset, this is shown to provide a better precision-recall tradeoff and to achieve a higher average Dice similarity coefficient. We also show that by using this soft mask scheme we can improve the network segmentation performance when compared to a second independent expert.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09263](http://arxiv.org/abs/1901.09263)

##### PDF
[http://arxiv.org/pdf/1901.09263](http://arxiv.org/pdf/1901.09263)

