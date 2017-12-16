---
layout: post
title: "Sparse-to-Dense: Depth Prediction from Sparse Depth Samples and a Single Image"
date: 2017-09-21 18:50:04
categories: arXiv_CV
tags: arXiv_CV Sparse Prediction SLAM
author: Fangchang Ma, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of dense depth prediction from a sparse set of depth measurements and a single RGB image. Since depth estimation from monocular images alone is inherently ambiguous and unreliable, we introduce additional sparse depth samples, which are either collected from a low-resolution depth sensor or computed from SLAM, to attain a higher level of robustness and accuracy. We propose the use of a single regression network to learn directly from the RGB-D raw data, and explore the impact of number of depth samples on prediction accuracy. Our experiments show that, as compared to using only RGB images, the addition of 100 spatially random depth samples reduces the prediction root-mean-square error by half in the NYU-Depth-v2 indoor dataset. It also boosts the percentage of reliable prediction from 59% to 92% on the more challenging KITTI driving dataset. We demonstrate two applications of the proposed algorithm: serving as a plug-in module in SLAM to convert sparse maps to dense maps, and creating much denser point clouds from low-resolution LiDARs. Codes and video demonstration are publicly available.

##### Abstract (translated by Google)
我们考虑从深度测量稀疏集合和单个RGB图像中预测稠密深度的问题。由于从单眼图像的深度估计本身是模糊的和不可靠的，我们引入额外的稀疏深度样本，这是从一个低分辨率深度传感器收集或从SLAM计算，以获得更高水平的鲁棒性和准确性。我们建议使用单一回归网络直接从RGB-D原始数据中学习，并探索深度样本数量对预测精度的影响。我们的实验表明，与仅使用RGB图像相比，在NYU-Depth-v2室内数据集中，添加100个空间随机深度样本可将预测的均方根误差减少一半。它也提高了KITTI驾驶数据集的可靠性预测比例，从59％提高到92％。我们演示了该算法的两个应用：作为SLAM中的插件模块将稀疏映射转换为密集映射，并从低分辨率LiDAR创建更密集的点云。代码和视频演示是公开可用的。

##### URL
[https://arxiv.org/abs/1709.07492](https://arxiv.org/abs/1709.07492)

##### PDF
[https://arxiv.org/pdf/1709.07492](https://arxiv.org/pdf/1709.07492)

