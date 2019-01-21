---
layout: post
title: "ULDor: A Universal Lesion Detector for CT Scans with Pseudo Masks and Hard Negative Example Mining"
date: 2019-01-18 17:59:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Youbao Tang, Ke Yan, Yuxing Tang, Jiamin Liu, Jing Xiao, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic lesion detection from computed tomography (CT) scans is an important task in medical imaging analysis. It is still very challenging due to similar appearances (e.g. intensity and texture) between lesions and other tissues, making it especially difficult to develop a universal lesion detector. Instead of developing a specific-type lesion detector, this work builds a Universal Lesion Detector (ULDor) based on Mask R-CNN, which is able to detect all different kinds of lesions from whole body parts. As a state-of-the-art object detector, Mask R-CNN adds a branch for predicting segmentation masks on each Region of Interest (RoI) to improve the detection performance. However, it is almost impossible to manually annotate a large-scale dataset with pixel-level lesion masks to train the Mask R-CNN for lesion detection. To address this problem, this work constructs a pseudo mask for each lesion region that can be considered as a surrogate of the real mask, based on which the Mask R-CNN is employed for lesion detection. On the other hand, this work proposes a hard negative example mining strategy to reduce the false positives for improving the detection performance. Experimental results on the NIH DeepLesion dataset demonstrate that the ULDor is enhanced using pseudo masks and the proposed hard negative example mining strategy and achieves a sensitivity of 86.21% with five false positives per image.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06359](http://arxiv.org/abs/1901.06359)

##### PDF
[http://arxiv.org/pdf/1901.06359](http://arxiv.org/pdf/1901.06359)

