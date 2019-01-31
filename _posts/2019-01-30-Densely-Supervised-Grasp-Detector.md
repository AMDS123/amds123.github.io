---
layout: post
title: "Densely Supervised Grasp Detector"
date: 2019-01-30 03:09:38
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Inference Deep_Learning Detection
author: Umar Asif, Jianbin Tang, Stefan Harrer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents Densely Supervised Grasp Detector (DSGD), a deep learning framework which combines CNN structures with layer-wise feature fusion and produces grasps and their confidence scores at different levels of the image hierarchy (i.e., global-, region-, and pixel-levels). % Specifically, at the global-level, DSGD uses the entire image information to predict a grasp. At the region-level, DSGD uses a region proposal network to identify salient regions in the image and predicts a grasp for each salient region. At the pixel-level, DSGD uses a fully convolutional network and predicts a grasp and its confidence at every pixel. % During inference, DSGD selects the most confident grasp as the output. This selection from hierarchically generated grasp candidates overcomes limitations of the individual models. % DSGD outperforms state-of-the-art methods on the Cornell grasp dataset in terms of grasp accuracy. % Evaluation on a multi-object dataset and real-world robotic grasping experiments show that DSGD produces highly stable grasps on a set of unseen objects in new environments. It achieves 97% grasp detection accuracy and 90% robotic grasping success rate with real-time inference speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03962](http://arxiv.org/abs/1810.03962)

##### PDF
[http://arxiv.org/pdf/1810.03962](http://arxiv.org/pdf/1810.03962)

