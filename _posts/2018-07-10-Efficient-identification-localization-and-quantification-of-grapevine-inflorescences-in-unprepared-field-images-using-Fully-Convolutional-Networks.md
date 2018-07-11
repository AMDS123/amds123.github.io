---
layout: post
title: "Efficient identification, localization and quantification of grapevine inflorescences in unprepared field images using Fully Convolutional Networks"
date: 2018-07-10 17:46:40
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Prediction
author: Robert Rudolph, Katja Herzog, Reinhard T&#xf6;pfer, Volker Steinhage
mathjax: true
---

* content
{:toc}

##### Abstract
Yield and its prediction is one of the most important tasks in grapevine breeding purposes and vineyard management. Commonly, this trait is estimated manually right before harvest by extrapolation, which mostly is labor-intensive, destructive and inaccurate. In the present study an automated image-based workflow was developed quantifying inflorescences and single flowers in unprepared field images of grapevines, i.e. no artificial background or light was applied. It is a novel approach for non-invasive, inexpensive and objective phenotyping with high-throughput. 
 First, image regions depicting inflorescences were identified and localized. This was done by segmenting the images into the classes "inflorescence" and "non-inflorescence" using a Fully Convolutional Network (FCN). Efficient image segmentation hereby is the most challenging step regarding the small geometry and dense distribution of flowers (several hundred flowers per inflorescence), similar color of all plant organs in the fore- and background as well as the circumstance that only approximately 5% of an image show inflorescences. The trained FCN achieved a mean Intersection Over Union (IOU) of 87.6% on the test data set. Finally, individual flowers were extracted from the "inflorescence"-areas using Circular Hough Transform. The flower extraction achieved a recall of 80.3% and a precision of 70.7% using the segmentation derived by the trained FCN model. 
 Summarized, the presented approach is a promising strategy in order to predict yield potential automatically in the earliest stage of grapevine development which is applicable for objective monitoring and evaluations of breeding material, genetic repositories or commercial vineyards.

##### Abstract (translated by Google)
产量及其预测是葡萄育种目的和葡萄园管理中最重要的任务之一。通常，这种特性在收获前通过外推手动估算，这主要是劳动密集型，破坏性和不准确性。在本研究中，开发了基于自动图像的工作流程，在无准备的葡萄藤田间图像中量化花序和单花，即没有施加人工背景或光。这是一种用于非侵入性，廉价且客观的表型分析的新方法，具有高通量。
 首先，识别和定位描绘花序的图像区域。这是通过使用完全卷积网络（FCN）将图像分割成“花序”和“非花序”类来完成的。因此，有效的图像分割是关于花的小几何和密集分布（每个花序数百花）的最具挑战性的步骤，前景和背景中所有植物器官的相似颜色以及仅约5％的花的情况。图像显示花序。训练有素的FCN在测试数据集上实现了87.6％的平均交叉联盟（IOU）。最后，使用圆形霍夫变换从“花序”区域提取单个花。使用由训练的FCN模型导出的分割，花提取实现80.3％的召回率和70.7％的精确度。
 总之，所提出的方法是一种有前途的策略，以便在葡萄开发的最早阶段自动预测产量潜力，其适用于对育种材料，遗传资源库或商业葡萄园的客观监测和评估。

##### URL
[http://arxiv.org/abs/1807.03770](http://arxiv.org/abs/1807.03770)

##### PDF
[http://arxiv.org/pdf/1807.03770](http://arxiv.org/pdf/1807.03770)

