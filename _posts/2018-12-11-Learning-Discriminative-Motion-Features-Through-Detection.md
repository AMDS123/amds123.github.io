---
layout: post
title: "Learning Discriminative Motion Features Through Detection"
date: 2018-12-11 01:06:56
categories: arXiv_CV
tags: arXiv_CV Salient Pose_Estimation Tracking Action_Recognition Detection Recognition
author: Gedas Bertasius, Christoph Feichtenhofer, Du Tran, Jianbo Shi, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
Despite huge success in the image domain, modern detection models such as Faster R-CNN have not been used nearly as much for video analysis. This is arguably due to the fact that detection models are designed to operate on single frames and as a result do not have a mechanism for learning motion representations directly from video. We propose a learning procedure that allows detection models such as Faster R-CNN to learn motion features directly from the RGB video data while being optimized with respect to a pose estimation task. Given a pair of video frames---Frame A and Frame B---we force our model to predict human pose in Frame A using the features from Frame B. We do so by leveraging deformable convolutions across space and time. Our network learns to spatially sample features from Frame B in order to maximize pose detection accuracy in Frame A. This naturally encourages our network to learn motion offsets encoding the spatial correspondences between the two frames. We refer to these motion offsets as DiMoFs (Discriminative Motion Features). 
 In our experiments we show that our training scheme helps learn effective motion cues, which can be used to estimate and localize salient human motion. Furthermore, we demonstrate that as a byproduct, our model also learns features that lead to improved pose detection in still-images, and better keypoint tracking. Finally, we show how to leverage our learned model for the tasks of spatiotemporal action localization and fine-grained action recognition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04172](http://arxiv.org/abs/1812.04172)

##### PDF
[http://arxiv.org/pdf/1812.04172](http://arxiv.org/pdf/1812.04172)

