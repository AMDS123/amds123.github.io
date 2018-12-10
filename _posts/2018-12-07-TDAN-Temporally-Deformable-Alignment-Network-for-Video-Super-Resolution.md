---
layout: post
title: "TDAN: Temporally Deformable Alignment Network for Video Super-Resolution"
date: 2018-12-07 03:58:43
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Prediction
author: Yapeng Tian, Yulun Zhang, Yun Fu, Chenliang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Video super-resolution (VSR) aims to restore a photo-realistic high-resolution (HR) video frame from both its corresponding low-resolution (LR) frame (reference frame) and multiple neighboring frames (supporting frames). Due to varying motion of cameras or objects, the reference frame and each support frame are not aligned. Therefore, temporal alignment is a challenging yet important problem for VSR. Previous VSR methods usually utilize optical flow between the reference frame and each supporting frame to wrap the supporting frame for temporal alignment. Therefore, the performance of these image-level wrapping-based models will highly depend on the prediction accuracy of optical flow, and inaccurate optical flow will lead to artifacts in the wrapped supporting frames, which also will be propagated into the reconstructed HR video frame. To overcome the limitation, in this paper, we propose a temporal deformable alignment network (TDAN) to adaptively align the reference frame and each supporting frame at the feature level without computing optical flow. The TDAN uses features from both the reference frame and each supporting frame to dynamically predict offsets of sampling convolution kernels. By using the corresponding kernels, TDAN transforms supporting frames to align with the reference frame. To predict the HR video frame, a reconstruction network taking aligned frames and the reference frame is utilized. Experimental results demonstrate the effectiveness of the proposed TDAN-based VSR model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02898](http://arxiv.org/abs/1812.02898)

##### PDF
[http://arxiv.org/pdf/1812.02898](http://arxiv.org/pdf/1812.02898)

