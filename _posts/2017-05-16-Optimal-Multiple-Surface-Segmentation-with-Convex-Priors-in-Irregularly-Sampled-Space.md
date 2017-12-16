---
layout: post
title: "Optimal Multiple Surface Segmentation with Convex Priors in Irregularly Sampled Space"
date: 2017-05-16 21:09:01
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Segmentation Face
author: Abhay Shah, Junjie Bai, Michael D. Abramoff, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Optimal surface segmentation is widely used in numerous medical image segmentation applications. However, nodes in the graph based optimal surface segmentation method typically encode uniformly distributed orthogonal voxels of the volume. Thus the segmentation cannot attain an accuracy greater than a single unit voxel, i.e. the distance between two adjoining nodes in graph space. Segmentation accuracy higher than a unit voxel is achievable by exploiting partial volume information in the voxels which shall result in non-equidistant spacing between adjoining graph nodes. This paper reports a generalized graph based optimal multiple surface segmentation method with convex priors which segments the target surfaces in irregularly sampled space. The proposed method allows non-equidistant spacing between the adjoining graph nodes to achieve subvoxel accurate segmentation by utilizing the partial volume information in the voxels. The partial volume information in the voxels is exploited by computing a displacement field from the original volume data to identify the subvoxel accurate centers within each voxel resulting in non-equidistant spacing between the adjoining graph nodes. The smoothness of each surface modelled as a convex constraint governs the connectivity and regularity of the surface. We employ an edge-based graph representation to incorporate the necessary constraints and the globally optimal solution is obtained by computing a minimum s-t cut. The proposed method was validated on 25 optical coherence tomography image volumes of the retina and 10 intravascular multi-frame ultrasound image datasets for subvoxel and super resolution segmentation accuracy. In all cases, the approach yielded highly accurate results. Our approach can be readily extended to higher-dimensional segmentations.

##### Abstract (translated by Google)
最佳的表面分割被广泛用于许多医学图像分割应用中。然而，基于图的最优表面分割方法中的节点通常编码体积的均匀分布的正交体素。因此，分割不能获得大于单个单位体素的精度，即在图形空间中两个相邻节点之间的距离。通过利用体素中的部分体积信息可以实现比单位体素更高的分割精度，这将导致相邻图形节点之间的非等距间隔。本文报道了一种基于广义图的最优多面凸曲面分割方法，该方法在不规则采样空间中对目标曲面进行分割。所提出的方法允许相邻图节点之间的非等距间隔通过利用体素中的部分体积信息来实现亚体素精确分割。通过从原始体数据计算位移场来识别体素中的部分体积信息，以识别每个体素内的子体元精确中心，从而导致相邻图节点之间的非等距间隔。每个曲面的平滑度被模拟成一个凸面约束来控制曲面的连通性和规律性。我们采用基于边缘的图形表示来结合必要的约束，并且通过计算最小s-t切割获得全局最优解。所提出的方法在25个光学相干断层扫描图像体积的视网膜和10个血管内多帧超声图像数据集验证了亚体素和超分辨率分割的准确性。在所有情况下，这种方法都能得到高度准确的结果。我们的方法可以很容易地扩展到更高维的分割。

##### URL
[https://arxiv.org/abs/1611.03059](https://arxiv.org/abs/1611.03059)

##### PDF
[https://arxiv.org/pdf/1611.03059](https://arxiv.org/pdf/1611.03059)

