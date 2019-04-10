---
layout: post
title: "Label Super Resolution with Inter-Instance Loss"
date: 2019-04-09 02:35:03
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Segmentation Semantic_Segmentation Prediction Detection
author: Maozheng Zhao, Le Hou, Han Le, Dimitris Samaras, Nebojsa Jojic, Danielle Fassler, Tahsin Kurc, Rajarsi Gupta, Kolya Malkin, Shahira Abousamra, Shroyer Kenneth, Joel Saltz
mathjax: true
---

* content
{:toc}

##### Abstract
For the task of semantic segmentation, high-resolution (pixel-level) ground truth is very expensive to collect, especially for high resolution images such as gigapixel pathology images. On the other hand, collecting low resolution labels (labels for a block of pixels) for these high resolution images is much more cost efficient. Conventional methods trained on these low-resolution labels are only capable of giving low-resolution predictions. The existing state-of-the-art label super resolution (LSR) method is capable of predicting high resolution labels, using only low-resolution supervision, given the joint distribution between low resolution and high resolution labels. However, it does not consider the inter-instance variance which is crucial in the ideal mathematical formulation. In this work, we propose a novel loss function modeling the inter-instance variance. We test our method on two real world applications: cell detection in multiplex immunohistochemistry (IHC) images, and infiltrating breast cancer region segmentation in histopathology slides. Experimental results show the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04429](http://arxiv.org/abs/1904.04429)

##### PDF
[http://arxiv.org/pdf/1904.04429](http://arxiv.org/pdf/1904.04429)

