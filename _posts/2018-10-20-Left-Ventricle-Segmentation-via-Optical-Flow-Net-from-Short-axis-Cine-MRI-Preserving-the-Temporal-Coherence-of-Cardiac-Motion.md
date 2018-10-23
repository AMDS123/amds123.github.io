---
layout: post
title: "Left Ventricle Segmentation via Optical-Flow-Net from Short-axis Cine MRI: Preserving the Temporal Coherence of Cardiac Motion"
date: 2018-10-20 05:41:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Wenjun Yan, Yuanyuan Wang, Zeju Li, Rob J. van der Geest, Qian Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative assessment of left ventricle (LV) function from cine MRI has significant diagnostic and prognostic value for cardiovascular disease patients. The temporal movement of LV provides essential information on the contracting/relaxing pattern of heart, which is keenly evaluated by clinical experts in clinical practice. Inspired by the expert way of viewing Cine MRI, we propose a new CNN module that is able to incorporate the temporal information into LV segmentation from cine MRI. In the proposed CNN, the optical flow (OF) between neighboring frames is integrated and aggregated at feature level, such that temporal coherence in cardiac motion can be taken into account during segmentation. The proposed module is integrated into the U-net architecture without need of additional training. Furthermore, dilated convolution is introduced to improve the spatial accuracy of segmentation. Trained and tested on the Cardiac Atlas database, the proposed network resulted in a Dice index of 95% and an average perpendicular distance of 0.9 pixels for the middle LV contour, significantly outperforming the original U-net that processes each frame individually. Notably, the proposed method improved the temporal coherence of LV segmentation results, especially at the LV apex and base where the cardiac motion is difficult to follow.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08753](http://arxiv.org/abs/1810.08753)

##### PDF
[http://arxiv.org/pdf/1810.08753](http://arxiv.org/pdf/1810.08753)

