---
layout: post
title: "Fast and accurate object detection in high resolution 4K and 8K video using GPUs"
date: 2018-10-24 18:00:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Vít Růžička, Franz Franchetti
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning has celebrated a lot of achievements on computer vision tasks such as object detection, but the traditionally used models work with relatively low resolution images. The resolution of recording devices is gradually increasing and there is a rising need for new methods of processing high resolution data. We propose an attention pipeline method which uses two staged evaluation of each image or video frame under rough and refined resolution to limit the total number of necessary evaluations. For both stages, we make use of the fast object detection model YOLO v2. We have implemented our model in code, which distributes the work across GPUs. We maintain high accuracy while reaching the average performance of 3-6 fps on 4K video and 2 fps on 8K video.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10551](https://arxiv.org/abs/1810.10551)

##### PDF
[https://arxiv.org/pdf/1810.10551](https://arxiv.org/pdf/1810.10551)

