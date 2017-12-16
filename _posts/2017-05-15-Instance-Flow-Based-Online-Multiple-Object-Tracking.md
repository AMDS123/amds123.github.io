---
layout: post
title: "Instance Flow Based Online Multiple Object Tracking"
date: 2017-05-15 14:14:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Semantic_Segmentation Detection
author: Sebastian Bullinger, Christoph Bodensteiner, Michael Arens
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to perform online Multiple Object Tracking (MOT) of known object categories in monocular video data. Current Tracking-by-Detection MOT approaches build on top of 2D bounding box detections. In contrast, we exploit state-of-the-art instance aware semantic segmentation techniques to compute 2D shape representations of target objects in each frame. We predict position and shape of segmented instances in subsequent frames by exploiting optical flow cues. We define an affinity matrix between instances of subsequent frames which reflects locality and visual similarity. The instance association is solved by applying the Hungarian method. We evaluate different configurations of our algorithm using the MOT 2D 2015 train dataset. The evaluation shows that our tracking approach is able to track objects with high relative motions. In addition, we provide results of our approach on the MOT 2D 2015 test set for comparison with previous works. We achieve a MOTA score of 32.1.

##### Abstract (translated by Google)
我们提出了一种在单目视频数据中执行已知对象类别的在线多目标跟踪（MOT）的方法。基于检测的电流跟踪MOT方法建立在2D边界框检测之上。相比之下，我们利用最先进的实例感知语义分割技术来计算每个帧中的目标对象的2D形状表示。我们通过利用光流提示预测后续帧中分割实例的位置和形状。我们定义了反映局部性和视觉相似性的后续帧实例之间的亲和性矩阵。实例关联通过应用匈牙利方法来解决。我们使用MOT 2D 2015火车数据集评估我们的算法的不同配置。评估表明，我们的跟踪方法能够跟踪相对运动较强的物体。另外，我们在MOT 2D 2015测试集上提供了我们的方法的结果，以便与之前的作品进行比较。我们达到32.1的MOTA得分。

##### URL
[https://arxiv.org/abs/1703.01289](https://arxiv.org/abs/1703.01289)

##### PDF
[https://arxiv.org/pdf/1703.01289](https://arxiv.org/pdf/1703.01289)

