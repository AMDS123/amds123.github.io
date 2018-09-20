---
layout: post
title: "Faster Training of Mask R-CNN by Focusing on Instance Boundaries"
date: 2018-09-19 08:54:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Survey Inference Prediction Detection
author: Roland S. Zimmermann, Julien N. Siems
mathjax: true
---

* content
{:toc}

##### Abstract
We present an auxiliary task to Mask R-CNN, an instance segmentation network, which leads to faster training of the mask head. Our addition to Mask R-CNN is a new prediction head, the Edge Agreement Head, which is inspired by the way human annotators perform instance segmentation. Human annotators copy the contour of an object instance and only indirectly the occupied instance area. Hence, the edges of instance masks are particularly useful as they characterize the instance well. The Edge Agreement Head therefore encourages predicted masks to have similar image gradients to the groundtruth mask using edge detection filters. We provide a detailed survey of loss combinations and show improvements on the MS COCO Mask metrics compared to using no additional loss. Our approach marginally increases the model size and adds no additional trainable model variables. While the computational costs are increased slightly, the increment is negligible considering the high computational cost of the Mask R-CNN architecture. As the additional network head is only relevant during training, inference speed remains unchanged compared to Mask R-CNN. In a default Mask R-CNN setup, we achieve a training speed up of 29% and an overall improvement of 8.1% on the MS COCO metrics compared to the baseline.

##### Abstract (translated by Google)
我们向Mask R-CNN（一个实例分割网络）提出了一个辅助任务，它可以加快掩模头的训练。我们对Mask R-CNN的补充是一个新的预测头，边缘协议头，它的灵感来自人类注释器执行实例分割的方式。人类注释器复制对象实例的轮廓，仅间接复制占用的实例区域。因此，实例掩码的边缘特别有用，因为它们很好地表征了实例。因此，边缘协议头使用边缘检测滤波器鼓励预测的掩模具有与地面掩模类似的图像梯度。我们提供了详细的损失组合调查，并显示了MS COCO Mask指标的改进，与不使用额外损失相比。我们的方法略微增加了模型尺寸，并且没有添加额外的可训练模型变量。虽然计算成本略有增加，但考虑到掩模R-CNN架构的高计算成本，增量可忽略不计。由于附加网络头仅在训练期间相关，因此与掩模R-CNN相比，推断速度保持不变。在默认的Mask R-CNN设置中，与基线相比，MS COCO指标的培训速度提高了29％，整体提升了8.1％。

##### URL
[http://arxiv.org/abs/1809.07069](http://arxiv.org/abs/1809.07069)

##### PDF
[http://arxiv.org/pdf/1809.07069](http://arxiv.org/pdf/1809.07069)

