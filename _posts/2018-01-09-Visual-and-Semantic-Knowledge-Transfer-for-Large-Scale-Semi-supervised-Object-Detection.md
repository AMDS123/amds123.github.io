---
layout: post
title: "Visual and Semantic Knowledge Transfer for Large Scale Semi-supervised Object Detection"
date: 2018-01-09 21:29:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Yuxing Tang, Josiah Wang, Xiaofang Wang, Boyang Gao, Emmanuel Dellandrea, Robert Gaizauskas, Liming Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep CNN-based object detection systems have achieved remarkable success on several large-scale object detection benchmarks. However, training such detectors requires a large number of labeled bounding boxes, which are more difficult to obtain than image-level annotations. Previous work addresses this issue by transforming image-level classifiers into object detectors. This is done by modeling the differences between the two on categories with both image-level and bounding box annotations, and transferring this information to convert classifiers to detectors for categories without bounding box annotations. We improve this previous work by incorporating knowledge about object similarities from visual and semantic domains during the transfer process. The intuition behind our proposed method is that visually and semantically similar categories should exhibit more common transferable properties than dissimilar categories, e.g. a better detector would result by transforming the differences between a dog classifier and a dog detector onto the cat class, than would by transforming from the violin class. Experimental results on the challenging ILSVRC2013 detection dataset demonstrate that each of our proposed object similarity based knowledge transfer methods outperforms the baseline methods. We found strong evidence that visual similarity and semantic relatedness are complementary for the task, and when combined notably improve detection, achieving state-of-the-art detection performance in a semi-supervised setting.

##### Abstract (translated by Google)
基于CNN的深度目标检测系统在多个大型目标检测基准上取得了显着的成功。然而，训练这样的检测器需要大量的标记边界框，这比图像级注释更难获得。以前的工作通过将图像级分类器转换为对象检测器来解决这个问题。这是通过建模两个类别之间的差异，使用图像级别和边界框注释来完成的，并且将这些信息转换成分类器，以将检测器转换为不带有框注释的类别。我们通过在转换过程中整合来自视觉和语义领域的对象相似性知识来改进以前的工作。我们提出的方法背后的直觉是，视觉和语义上相似的类别应该表现出比不同类别更常见的可传递性质，通过将狗分类器和狗检测器之间的差异转换成猫类，将比通过从小提琴类转换而得到更好的检测器。在具有挑战性的ILSVRC2013检测数据集的实验结果表明，我们提出的每个基于对象相似性的知识转移方法都优于基​​线方法。我们发现有力的证据表明，视觉相似性和语义相关性对于任务是互补的，并且当组合显着改善检测时，在半监督设置中实现最新的检测性能。

##### URL
[https://arxiv.org/abs/1801.03145](https://arxiv.org/abs/1801.03145)

##### PDF
[https://arxiv.org/pdf/1801.03145](https://arxiv.org/pdf/1801.03145)

