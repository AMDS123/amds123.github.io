---
layout: post
title: "DetNAS: Backbone Search for Object Detection"
date: 2019-06-10 15:00:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection NAS Image_Classification Classification Detection
author: Yukang Chen, Tong Yang, Xiangyu Zhang, Gaofeng Meng, Chunhong Pan, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors are usually equipped with backbone networks designed for image classification. It might be sub-optimal because of the gap between the tasks of image classification and object detection. In this work, we present DetNAS to use Neural Architecture Search (NAS) for the design of better backbones for object detection. It is non-trivial because detection trainings typically need ImageNet pre-training while NAS systems require accuracies on the target detection task as supervisory signals. Based on the technique of one-shot supernet, which contains all possible networks in the search space, we propose a framework for backbone search on object detection. We train the supernet under the typical detector training schedule: ImageNet pre-training and detection fine-tuning. Then, the architecture search is performed on the trained supernet, using the detection task as the guidance. This framework makes NAS on backbones very efficient. In experiments, we show the effectiveness of DetNAS on various detectors, for instance, one-stage RetinaNet and the two-stage FPN. We empirically find that networks searched on object detection shows consistent superiority compared to those searched on ImageNet classification. The resulting architecture achieves superior performance than ResNet-50 and ResNet-101 on COCO with much less FLOPs complexity.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.10979](https://arxiv.org/abs/1903.10979)

##### PDF
[https://arxiv.org/pdf/1903.10979](https://arxiv.org/pdf/1903.10979)

