---
layout: post
title: "ExpandNet: A Deep Convolutional Neural Network for High Dynamic Range Expansion from Low Dynamic Range Content"
date: 2019-09-04 08:10:25
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Demetris Marnerides, Thomas Bashford-Rogers, Jonathan Hatchett, Kurt Debattista
mathjax: true
---

* content
{:toc}

##### Abstract
High dynamic range (HDR) imaging provides the capability of handling real world lighting as opposed to the traditional low dynamic range (LDR) which struggles to accurately represent images with higher dynamic range. However, most imaging content is still available only in LDR. This paper presents a method for generating HDR content from LDR content based on deep Convolutional Neural Networks (CNNs) termed ExpandNet. ExpandNet accepts LDR images as input and generates images with an expanded range in an end-to-end fashion. The model attempts to reconstruct missing information that was lost from the original signal due to quantization, clipping, tone mapping or gamma correction. The added information is reconstructed from learned features, as the network is trained in a supervised fashion using a dataset of HDR images. The approach is fully automatic and data driven; it does not require any heuristics or human expertise. ExpandNet uses a multiscale architecture which avoids the use of upsampling layers to improve image quality. The method performs well compared to expansion/inverse tone mapping operators quantitatively on multiple metrics, even for badly exposed inputs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.02266](http://arxiv.org/abs/1803.02266)

##### PDF
[http://arxiv.org/pdf/1803.02266](http://arxiv.org/pdf/1803.02266)

