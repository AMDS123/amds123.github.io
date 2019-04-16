---
layout: post
title: "DetNet: A Backbone network for Object Detection"
date: 2018-04-19 06:36:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Image_Classification Classification Detection
author: Zeming Li, Chao Peng, Gang Yu, Xiangyu Zhang, Yangdong Deng, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent CNN based object detectors, no matter one-stage methods like YOLO, SSD, and RetinaNe or two-stage detectors like Faster R-CNN, R-FCN and FPN are usually trying to directly finetune from ImageNet pre-trained models designed for image classification. There has been little work discussing on the backbone feature extractor specifically designed for the object detection. More importantly, there are several differences between the tasks of image classification and object detection. 1. Recent object detectors like FPN and RetinaNet usually involve extra stages against the task of image classification to handle the objects with various scales. 2. Object detection not only needs to recognize the category of the object instances but also spatially locate the position. Large downsampling factor brings large valid receptive field, which is good for image classification but compromises the object location ability. Due to the gap between the image classification and object detection, we propose DetNet in this paper, which is a novel backbone network specifically designed for object detection. Moreover, DetNet includes the extra stages against traditional backbone network for image classification, while maintains high spatial resolution in deeper layers. Without any bells and whistles, state-of-the-art results have been obtained for both object detection and instance segmentation on the MSCOCO benchmark based on our DetNet~(4.8G FLOPs) backbone. The code will be released for the reproduction.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.06215](https://arxiv.org/abs/1804.06215)

##### PDF
[https://arxiv.org/pdf/1804.06215](https://arxiv.org/pdf/1804.06215)

