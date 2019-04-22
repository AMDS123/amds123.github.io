---
layout: post
title: "XLSor: A Robust and Accurate Lung Segmentor on Chest X-Rays Using Criss-Cross Attention and Customized Radiorealistic Abnormalities Generation"
date: 2019-04-19 15:22:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Youbao Tang, Yuxing Tang, Jing Xiao, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework for lung segmentation in chest X-rays. It consists of two key contributions, a criss-cross attention based segmentation network and radiorealistic chest X-ray image synthesis (i.e. a synthesized radiograph that appears anatomically realistic) for data augmentation. The criss-cross attention modules capture rich global contextual information in both horizontal and vertical directions for all the pixels thus facilitating accurate lung segmentation. To reduce the manual annotation burden and to train a robust lung segmentor that can be adapted to pathological lungs with hazy lung boundaries, an image-to-image translation module is employed to synthesize radiorealistic abnormal CXRs from the source of normal ones for data augmentation. The lung masks of synthetic abnormal CXRs are propagated from the segmentation results of their normal counterparts, and then serve as pseudo masks for robust segmentor training. In addition, we annotate 100 CXRs with lung masks on a more challenging NIH Chest X-ray dataset containing both posterioranterior and anteroposterior views for evaluation. Extensive experiments validate the robustness and effectiveness of the proposed framework. The code and data can be found from https://github.com/rsummers11/CADLab/tree/master/Lung_Segmentation_XLSor .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09229](http://arxiv.org/abs/1904.09229)

##### PDF
[http://arxiv.org/pdf/1904.09229](http://arxiv.org/pdf/1904.09229)

