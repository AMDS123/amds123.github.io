---
layout: post
title: "Multiple Instance Curriculum Learning for Weakly Supervised Object Detection"
date: 2017-11-25 05:08:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Detection
author: Siyang Li, Xiangxin Zhu, Qin Huang, Hao Xu, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
When supervising an object detector with weakly labeled data, most existing approaches are prone to trapping in the discriminative object parts, e.g., finding the face of a cat instead of the full body, due to lacking the supervision on the extent of full objects. To address this challenge, we incorporate object segmentation into the detector training, which guides the model to correctly localize the full objects. We propose the multiple instance curriculum learning (MICL) method, which injects curriculum learning (CL) into the multiple instance learning (MIL) framework. The MICL method starts by automatically picking the easy training examples, where the extent of the segmentation masks agree with detection bounding boxes. The training set is gradually expanded to include harder examples to train strong detectors that handle complex images. The proposed MICL method with segmentation in the loop outperforms the state-of-the-art weakly supervised object detectors by a substantial margin on the PASCAL VOC datasets.

##### Abstract (translated by Google)
当监视具有弱标记数据的物体检测器时，由于缺乏对全物体范围的监督，大多数现有的方法倾向于陷入有区别的物体部分，例如找到猫的脸而不是全身。为了应对这一挑战，我们将对象分割合并到检测器训练中，指导模型正确定位整个对象。我们提出多元实例课程学习（MICL）方法，它将课程学习（CL）注入到多实例学习（MIL）框架中。 MICL方法从自动挑选简单训练实例开始，其中分割掩模的范围与检测边界框一致。训练集逐渐扩大到包括更强的示例来训练处理复杂图像的强检测器。在环路中提出的具有分割的MICL方法在PASCAL VOC数据集上优于现有技术的弱监督物体检测器。

##### URL
[https://arxiv.org/abs/1711.09191](https://arxiv.org/abs/1711.09191)

