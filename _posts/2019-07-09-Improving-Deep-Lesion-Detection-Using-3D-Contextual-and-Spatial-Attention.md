---
layout: post
title: "Improving Deep Lesion Detection Using 3D Contextual and Spatial Attention"
date: 2019-07-09 09:19:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Qingyi Tao, Zongyuan Ge, Jianfei Cai, Jianxiong Yin, Simon See
mathjax: true
---

* content
{:toc}

##### Abstract
Lesion detection from computed tomography (CT) scans is challenging compared to natural object detection because of two major reasons: small lesion size and small inter-class variation. Firstly, the lesions usually only occupy a small region in the CT image. The feature of such small region may not be able to provide sufficient information due to its limited spatial feature resolution. Secondly, in CT scans, the lesions are often indistinguishable from the background since the lesion and non-lesion areas may have very similar appearances. To tackle both problems, we need to enrich the feature representation and improve the feature discriminativeness. Therefore, we introduce a dual-attention mechanism to the 3D contextual lesion detection framework, including the cross-slice contextual attention to selectively aggregate the information from different slices through a soft re-sampling process. Moreover, we propose intra-slice spatial attention to focus the feature learning in the most prominent regions. Our method can be easily trained end-to-end without adding heavy overhead on the base detection network. We use DeepLesion dataset and train a universal lesion detector to detect all kinds of lesions such as liver tumors, lung nodules, and so on. The results show that our model can significantly boost the results of the baseline lesion detector (with 3D contextual information) but using much fewer slices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04052](http://arxiv.org/abs/1907.04052)

##### PDF
[http://arxiv.org/pdf/1907.04052](http://arxiv.org/pdf/1907.04052)

