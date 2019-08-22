---
layout: post
title: "InstaBoost: Boosting Instance Segmentation via Probability Map Guided Copy-Pasting"
date: 2019-08-21 11:21:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Inference
author: Hao-Shu Fang, Jianhua Sun, Runzhong Wang, Minghao Gou, Yong-Lu Li, Cewu Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Instance segmentation requires a large number of training samples to achieve satisfactory performance and benefits from proper data augmentation. To enlarge the training set and increase the diversity, previous methods have investigated using data annotation from other domain (e.g. bbox, point) in a weakly supervised mechanism. In this paper, we present a simple, efficient and effective method to augment the training set using the existing instance mask annotations. Exploiting the pixel redundancy of the background, we are able to improve the performance of Mask R-CNN for 1.7 mAP on COCO dataset and 3.3 mAP on Pascal VOC dataset by simply introducing random jittering to objects. Furthermore, we propose a location probability map based approach to explore the feasible locations that objects can be placed based on local appearance similarity. With the guidance of such map, we boost the performance of R101-Mask R-CNN on instance segmentation from 35.7 mAP to 37.9 mAP without modifying the backbone or network structure. Our method is simple to implement and does not increase the computational complexity. It can be integrated into the training pipeline of any instance segmentation model without affecting the training and inference efficiency. Our code and models have been released at https://github.com/GothicAi/InstaBoost

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07801](http://arxiv.org/abs/1908.07801)

##### PDF
[http://arxiv.org/pdf/1908.07801](http://arxiv.org/pdf/1908.07801)

