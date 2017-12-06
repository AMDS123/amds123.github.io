---
layout: post
title: "Window-Object Relationship Guided Representation Learning for Generic Object Detections"
date: 2015-12-09 03:32:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Xingyu Zeng, Wanli Ouyang, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In existing works that learn representation for object detection, the relationship between a candidate window and the ground truth bounding box of an object is simplified by thresholding their overlap. This paper shows information loss in this simplification and picks up the relative location/size information discarded by thresholding. We propose a representation learning pipeline to use the relationship as supervision for improving the learned representation in object detection. Such relationship is not limited to object of the target category, but also includes surrounding objects of other categories. We show that image regions with multiple contexts and multiple rotations are effective in capturing such relationship during the representation learning process and in handling the semantic and visual variation caused by different window-object configurations. Experimental results show that the representation learned by our approach can improve the object detection accuracy by 6.4% in mean average precision (mAP) on ILSVRC2014. On the challenging ILSVRC2014 test dataset, 48.6% mAP is achieved by our single model and it is the best among published results. On PASCAL VOC, it outperforms the state-of-the-art result of Fast RCNN by 3.3% in absolute mAP.

##### Abstract (translated by Google)
在现有的学习物体检测表示的作品中，候选窗口与对象的地面真实边界框之间的关系通过对其重叠进行阈值化来简化。本文通过这种简化显示信息丢失，并提取阈值丢弃的相对位置/大小信息。我们提出了一个表示学习管道，使用关系作为监督，以改善学习表示在对象检测。这样的关系不限于对象范畴的对象，也包含其他范畴的对象。我们表明，在表示学习过程中以及处理由不同窗口对象配置引起的语义和视觉变化时，具有多个上下文和多个旋转的图像区域有效地捕获这种关系。实验结果表明，我们的方法学习的表示可以提高对ILSVRC2014平均精度（mAP）的6.4％的目标检测精度。在具有挑战性的ILSVRC2014测试数据集中，48.6％的mAP是通过我们的单一模型实现的，并且是公布的结果中最好的。在PASCAL VOC方面，它比绝对mAP中快速RCNN的最新结果高出3.3％。

##### URL
[https://arxiv.org/abs/1512.02736](https://arxiv.org/abs/1512.02736)

