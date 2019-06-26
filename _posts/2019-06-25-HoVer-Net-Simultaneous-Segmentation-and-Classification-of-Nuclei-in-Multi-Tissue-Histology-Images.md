---
layout: post
title: "HoVer-Net: Simultaneous Segmentation and Classification of Nuclei in Multi-Tissue Histology Images"
date: 2019-06-25 10:52:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Classification Quantitative
author: Simon Graham, Quoc Dang Vu, Shan E Ahmed Raza, Ayesha Azam, Yee Wah Tsang, Jin Tae Kwak, Nasir Rajpoot
mathjax: true
---

* content
{:toc}

##### Abstract
Nuclear segmentation and classification within Haematoxylin &amp; Eosin stained histology images is a fundamental prerequisite in the digital pathology work-flow. The development of automated methods for nuclear segmentation and classification enables the quantitative analysis of tens of thousands of nuclei within a whole-slide pathology image, opening up possibilities of further analysis of large-scale nuclear morphometry. However, automated nuclear segmentation and classification is faced with a major challenge in that there are several different types of nuclei, some of them exhibiting large intra-class variability such as the tumour cells. Additionally, some of the nuclei are often clustered together. To address these challenges, we present a novel convolutional neural network for simultaneous nuclear segmentation and classification that leverages the instance-rich information encoded within the vertical and horizontal distances of nuclear pixels to their centres of mass. These distances are then utilised to separate clustered nuclei, resulting in an accurate segmentation, particularly in areas with overlapping instances. Then for each segmented instance, the network predicts the type of nucleus via a devoted up-sampling branch. We demonstrate state-of-the-art performance compared to other methods on multiple independent multi-tissue histology image datasets. As part of this work, we introduce a new dataset of Haematoxylin &amp; Eosin stained colorectal adenocarcinoma image tiles, containing 24,319 exhaustively annotated nuclei with associated class labels.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06499](http://arxiv.org/abs/1812.06499)

##### PDF
[http://arxiv.org/pdf/1812.06499](http://arxiv.org/pdf/1812.06499)

