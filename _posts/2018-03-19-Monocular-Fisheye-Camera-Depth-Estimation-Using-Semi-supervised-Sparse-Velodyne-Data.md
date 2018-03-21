---
layout: post
title: "Monocular Fisheye Camera Depth Estimation Using Semi-supervised Sparse Velodyne Data"
date: 2018-03-19 08:31:15
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference
author: Varun Ravi Kumar, Stefan Milz, Martin Simon, Christian Witt, Karl Amende, Johannes Petzold, Senthil Yogamani
mathjax: true
---

* content
{:toc}

##### Abstract
Near field depth estimation around a self driving car is an important function that can be achieved by four wide angle fisheye cameras having a field of view of over 180. CNN based depth estimation produce state of the art results, but progress is hindered because depth annotation cannot be obtained manually. Synthetic datasets are commonly used but they have limitations. For instance, they do not capture the extensive variability in the appearance of objects like vehicles present in real datasets. There is also a domain shift while performing inference on natural images illustrated by many attempts to handle the domain adaptation explicitly. In this work, we explore an alternate approach of training using sparse LIDAR data as ground truth for depth estimation for fisheye camera. We built our own dataset using our self\hyp driving car setup which has a 64 beam Velodyne LIDAR and four wide angle fisheye cameras. LIDAR data projected onto the image plane is sparse and hence viewed as semi supervision for dense depth estimation. To handle the difference in view points of LIDAR and fisheye camera, an occlusion resolution mechanism was implemented. We started with Eigen's multiscale convolutional network architecture and improved by modifying activation function and optimizer. We obtained promising results on our dataset with RMSE errors better than the state of the art results obtained on KITTI because of vast amounts of training data. Our model runs at 20 fps on an embedded platform Nvidia TX2.

##### Abstract (translated by Google)
自动驾驶汽车周围的近场深度估计是一个重要的功能，可以通过视场超过180°的四台广角鱼眼摄像机实现。基于CNN的深度估计可产生最新的结果，但进展受阻，因为深度标注无法手动获取。通常使用合成数据集，但它们有局限性。例如，它们没有捕获像真实数据集中存在的车辆这样的物体的外观的广泛变化。在对自然图像进行推理时，还有一个域转移，通过很多尝试来明确处理域自适应。在这项工作中，我们探索了一种使用稀疏LIDAR数据作为鱼眼相机深度估计的地面实况的替代培训方法。我们使用我们自己的hyp驱动汽车设置建立了我们自己的数据集，该汽车设置有64个光束Velodyne LIDAR和4个广角鱼眼相机。投影到图像平面上的激光雷达数据稀疏，因此被视为密集深度估计的半监督。为了处理激光雷达和鱼眼相机的视点差异，实施了遮挡解决机制。我们从Eigen的多尺度卷积网络体系结构开始，并通过修改激活函数和优化器进行了改进。由于大量的训练数据，我们在我们的数据集上获得了有希望的结果，RMSE误差优于KITTI获得的最新结果。我们的模型在嵌入式平台Nvidia TX2上运行速度为20 fps。

##### URL
[https://arxiv.org/abs/1803.06192](https://arxiv.org/abs/1803.06192)

##### PDF
[https://arxiv.org/pdf/1803.06192](https://arxiv.org/pdf/1803.06192)

