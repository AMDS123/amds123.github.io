---
layout: post
title: "Occlusion-Aware Object Localization, Segmentation and Pose Estimation"
date: 2015-07-27 18:16:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Detection
author: Samarth Brahmbhatt, Heni Ben Amor, Henrik Christensen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning approach for localization and segmentation of objects in an image in a manner that is robust to partial occlusion. Our algorithm produces a bounding box around the full extent of the object and labels pixels in the interior that belong to the object. Like existing segmentation aware detection approaches, we learn an appearance model of the object and consider regions that do not fit this model as potential occlusions. However, in addition to the established use of pairwise potentials for encouraging local consistency, we use higher order potentials which capture information at the level of im- age segments. We also propose an efficient loss function that targets both localization and segmentation performance. Our algorithm achieves 13.52% segmentation error and 0.81 area under the false-positive per image vs. recall curve on average over the challenging CMU Kitchen Occlusion Dataset. This is a 42.44% decrease in segmentation error and a 16.13% increase in localization performance compared to the state-of-the-art. Finally, we show that the visibility labelling produced by our algorithm can make full 3D pose estimation from a single image robust to occlusion.

##### Abstract (translated by Google)
我们提出了一种学习方法，以一种对部分遮挡强健的方式对图像中的对象进行定位和分割。我们的算法在对象的整个范围内生成一个边界框，并标记属于该对象的内部像素。像现有的分割感知检测方法一样，我们学习对象的外观模型，并考虑不适合该模型的区域作为潜在的遮挡。然而，除了成对使用成对潜力来鼓励局部一致性之外，我们还使用更高阶潜能来捕获图像层面的信息。我们还提出了一个高效的损失函数，既针对本地化又针对细分性能。在具有挑战性的CMU厨房遮挡数据集上，我们的算法实现了13.52％的分割误差和每个图像假阳性下的0.81面积与平均检索曲线。与最先进的技术相比，分割误差降低了42.44％，本地化性能提高了16.13％。最后，我们展示了由我们的算法产生的可见性标签可以使得从单个图像鲁棒性到遮挡的全3D姿态估计。

##### URL
[https://arxiv.org/abs/1507.07882](https://arxiv.org/abs/1507.07882)

##### PDF
[https://arxiv.org/pdf/1507.07882](https://arxiv.org/pdf/1507.07882)

