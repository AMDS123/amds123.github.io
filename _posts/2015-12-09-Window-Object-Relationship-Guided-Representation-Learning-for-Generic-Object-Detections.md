---
layout: post
title: "Window-Object Relationship Guided Representation Learning for Generic Object Detections"
date: 2015-12-09 03:32:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Represenation_Learning Detection Relation
author: Xingyu Zeng, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In existing works that learn representation for object detection, the relationship between a candidate window and the ground truth bounding box of an object is simplified by thresholding their overlap. This paper shows information loss in this simplification and picks up the relative location/size information discarded by thresholding. We propose a representation learning pipeline to use the relationship as supervision for improving the learned representation in object detection. Such relationship is not limited to object of the target category, but also includes surrounding objects of other categories. We show that image regions with multiple contexts and multiple rotations are effective in capturing such relationship during the representation learning process and in handling the semantic and visual variation caused by different window-object configurations. Experimental results show that the representation learned by our approach can improve the object detection accuracy by 6.4% in mean average precision (mAP) on ILSVRC2014. On the challenging ILSVRC2014 test dataset, 48.6% mAP is achieved by our single model and it is the best among published results. On PASCAL VOC, it outperforms the state-of-the-art result of Fast RCNN by 3.3% in absolute mAP.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1512.02736](https://arxiv.org/abs/1512.02736)

##### PDF
[https://arxiv.org/pdf/1512.02736](https://arxiv.org/pdf/1512.02736)

