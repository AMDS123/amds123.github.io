---
layout: post
title: "Fast Video Object Segmentation via Mask Transfer Network"
date: 2019-08-28 13:31:34
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tao Zhuo, Zhiyong Cheng, Mohan Kankanhalli
mathjax: true
---

* content
{:toc}

##### Abstract
Accuracy and processing speed are two important factors that affect the use of video object segmentation (VOS) in real applications. With the advanced techniques of deep neural networks, the accuracy has been significantly improved, however, the speed is still far below the real-time needs because of the complicated network design, such as the requirement of the first frame fine-tuning step. To overcome this limitation, we propose a novel mask transfer network (MTN), which can greatly boost the processing speed of VOS and also achieve a reasonable accuracy. The basic idea of MTN is to transfer the reference mask to the target frame via an efficient global pixel matching strategy. The global pixel matching between the reference frame and the target frame is to ensure good matching results. To enhance the matching speed, we perform the matching on a downsampled feature map with 1/32 of the original frame size. At the same time, to preserve the detailed mask information in such a small feature map, a mask network is designed to encode the annotated mask information with 512 channels. Finally, an efficient feature warping method is used to transfer the encoded reference mask to the target frame. Based on this design, our method avoids the fine-tuning step on the first frame and does not rely on the temporal cues and particular object categories. Therefore, it runs very fast and can be conveniently trained only with images, as well as being robust to unseen objects. Experiments on the DAVIS datasets demonstrate that MTN can achieve a speed of 37 fps, and also shows a competitive accuracy in comparison to the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10717](http://arxiv.org/abs/1908.10717)

##### PDF
[http://arxiv.org/pdf/1908.10717](http://arxiv.org/pdf/1908.10717)

