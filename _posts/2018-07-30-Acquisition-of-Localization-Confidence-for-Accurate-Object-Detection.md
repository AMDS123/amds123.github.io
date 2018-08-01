---
layout: post
title: "Acquisition of Localization Confidence for Accurate Object Detection"
date: 2018-07-30 21:36:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Borui Jiang, Ruixuan Luo, Jiayuan Mao, Tete Xiao, Yuning Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Modern CNN-based object detectors rely on bounding box regression and non-maximum suppression to localize objects. While the probabilities for class labels naturally reflect classification confidence, localization confidence is absent. This makes properly localized bounding boxes degenerate during iterative regression or even suppressed during NMS. In the paper we propose IoU-Net learning to predict the IoU between each detected bounding box and the matched ground-truth. The network acquires this confidence of localization, which improves the NMS procedure by preserving accurately localized bounding boxes. Furthermore, an optimization-based bounding box refinement method is proposed, where the predicted IoU is formulated as the objective. Extensive experiments on the MS-COCO dataset show the effectiveness of IoU-Net, as well as its compatibility with and adaptivity to several state-of-the-art object detectors.

##### Abstract (translated by Google)
现代的基于CNN的物体检测器依靠边界框回归和非最大抑制来定位对象。虽然类标签的概率自然反映了分类置信度，但缺乏定位置信度。这使得正确定位的边界框在迭代回归期间退化或甚至在NMS期间被抑制。在本文中，我们提出了IoU-Net学习来预测每个检测到的边界框与匹配的地面实况之间的IoU。网络获得了本地化的信心，通过保留精确的本地化边界框来改进NMS过程。此外，提出了一种基于优化的边界框细化方法，其中将预测的IoU表示为目标。 MS-COCO数据集上的大量实验表明了IoU-Net的有效性，以及它与几种最先进的物体探测器的兼容性和适应性。

##### URL
[http://arxiv.org/abs/1807.11590](http://arxiv.org/abs/1807.11590)

##### PDF
[http://arxiv.org/pdf/1807.11590](http://arxiv.org/pdf/1807.11590)

