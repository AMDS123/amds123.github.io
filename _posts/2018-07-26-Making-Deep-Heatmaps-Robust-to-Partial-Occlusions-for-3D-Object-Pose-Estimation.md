---
layout: post
title: "Making Deep Heatmaps Robust to Partial Occlusions for 3D Object Pose Estimation"
date: 2018-07-26 06:38:54
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Prediction
author: Markus Oberweger, Mahdi Rad, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel method for robust and accurate 3D object pose estimation from a single color image under large occlusions. Following recent approaches, we first predict the 2D projections of 3D points related to the target object and then compute the 3D pose from these correspondences using a geometric method. Unfortunately, as the results of our experiments show, predicting these 2D projections using a regular CNN or a Convolutional Pose Machine is highly sensitive to partial occlusions, even when these methods are trained with partially occluded examples. Our solution is to predict heatmaps from multiple small patches independently and to accumulate the results to obtain accurate and robust predictions. Training subsequently becomes challenging because patches with similar appearances but different positions on the object correspond to different heatmaps. However, we provide a simple yet effective solution to deal with such ambiguities. We show that our approach outperforms existing methods on two challenging datasets: The Occluded LineMOD dataset and the YCB-Video dataset, both exhibiting cluttered scenes with highly occluded objects. Project website: https://www.tugraz.at/institute/icg/research/team-lepetit/research-projects/robust-object-pose-estimation/

##### Abstract (translated by Google)
我们介绍了一种新方法，用于在大的遮挡下从单个彩色图像中进行稳健和精确的3D物体姿态估计。根据最近的方法，我们首先预测与目标对象相关的3D点的2D投影，然后使用几何方法从这些对应关系计算3D姿势。不幸的是，正如我们的实验结果所示，使用常规CNN或卷积姿势机预测这些2D投影对部分遮挡非常敏感，即使这些方法是用部分遮挡的例子训练的。我们的解决方案是独立地预测来自多个小块的热图，并累积结果以获得准确和稳健的预测。随后的训练变得具有挑战性，因为具有相似外观但在物体上的不同位置的补片对应于不同的热图。但是，我们提供了一种简单而有效的解决方案来处理这种歧义。我们展示了我们的方法在两个具有挑战性的数据集上优于现有方法：Occluded LineMOD数据集和YCB-Video数据集，两者都展示了具有高度遮挡对象的杂乱场景。项目网站：https：//www.tugraz.at/institute/icg/research/team-lepetit/research-projects/robust-object-pose-estimation/

##### URL
[http://arxiv.org/abs/1804.03959](http://arxiv.org/abs/1804.03959)

##### PDF
[http://arxiv.org/pdf/1804.03959](http://arxiv.org/pdf/1804.03959)

