---
layout: post
title: "Multi-scale Aggregation R-CNN for 2D Multi-person Pose Estimation"
date: 2019-05-10 02:17:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Gyeongsik Moon, Ju Yong Chang, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-person pose estimation from a 2D image is challenging because it requires not only keypoint localization but also human detection. In state-of-the-art top-down methods, multi-scale information is a crucial factor for the accurate pose estimation because it contains both of local information around the keypoints and global information of the entire person. Although multi-scale information allows these methods to achieve the state-of-the-art performance, the top-down methods still require a huge amount of computation because they need to use an additional human detector to feed the cropped human image to their pose estimation model. To effectively utilize multi-scale information with the smaller computation, we propose a multi-scale aggregation R-CNN (MSA R-CNN). It consists of multi-scale RoIAlign block (MS-RoIAlign) and multi-scale keypoint head network (MS-KpsNet) which are designed to effectively utilize multi-scale information. Also, in contrast to previous top-down methods, the MSA R-CNN performs human detection and keypoint localization in a single model, which results in reduced computation. The proposed model achieved the best performance among single model-based methods and its results are comparable to those of separated model-based methods with a smaller amount of computation on the publicly available 2D multi-person keypoint localization dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03912](http://arxiv.org/abs/1905.03912)

##### PDF
[http://arxiv.org/pdf/1905.03912](http://arxiv.org/pdf/1905.03912)

