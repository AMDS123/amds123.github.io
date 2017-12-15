---
layout: post
title: "Fast and Robust Feature Matching for RGB-D Based Localization"
date: 2015-02-02 15:02:10
categories: arXiv_CV
tags: arXiv_CV
author: Miguel Heredia, Felix Endres, Wolfram Burgard, Rafael Sanz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel approach to global localization using an RGB-D camera in maps of visual features. For large maps, the performance of pure image matching techniques decays in terms of robustness and computational cost. Particularly, repeated occurrences of similar features due to repeating structure in the world (e.g., doorways, chairs, etc.) or missing associations between observations pose critical challenges to visual localization. We address these challenges using a two-step approach. We first estimate a candidate pose using few correspondences between features of the current camera frame and the feature map. The initial set of correspondences is established by proximity in feature space. The initial pose estimate is used in the second step to guide spatial matching of features in 3D, i.e., searching for associations where the image features are expected to be found in the map. A RANSAC algorithm is used to compute a fine estimation of the pose from the correspondences. Our approach clearly outperforms localization based on feature matching exclusively in feature space, both in terms of estimation accuracy and robustness to failure and allows for global localization in real time (30Hz).

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的方法来使用RGB-D相机在视觉特征的地图中进行全球定位。对于大型地图，纯图像匹配技术的性能在鲁棒性和计算成本方面衰减。特别地，由于世界上重复结构（例如，门道，椅子等）或观察之间的缺失关联而导致的类似特征的重复出现对视觉定位提出了严峻的挑战。我们采用两步法解决这些挑战。我们首先使用当前相机帧的特征和特征映射之间的少量对应来估计候选姿态。初始的对应关系由特征空间中的邻近性建立。在第二步中使用初始姿态估计来指导3D中的特征的空间匹配，即，搜索预期在地图中找到图像特征的关联。 RANSAC算法被用来根据对应关系计算姿态的精确估计。我们的方法明显优于仅基于特征空间中的特征匹配的定位，无论是在估计精度还是对失效的稳健性方面，并且允许实时（30Hz）的全局定位。

##### URL
[https://arxiv.org/abs/1502.00500](https://arxiv.org/abs/1502.00500)

##### PDF
[https://arxiv.org/pdf/1502.00500](https://arxiv.org/pdf/1502.00500)

