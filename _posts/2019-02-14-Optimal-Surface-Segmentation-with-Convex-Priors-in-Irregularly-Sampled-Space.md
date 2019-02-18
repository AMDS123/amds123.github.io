---
layout: post
title: "Optimal Surface Segmentation with Convex Priors in Irregularly Sampled Space"
date: 2019-02-14 19:38:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Abhay Shah, Michael D. Abramoff, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Optimal surface segmentation is a state-of-the-art method used for segmentation of multiple globally optimal surfaces in volumetric datasets. The method is widely used in numerous medical image segmentation applications. However, nodes in the graph based optimal surface segmentation method typically encode uniformly distributed orthogonal voxels of the volume. Thus the segmentation cannot attain an accuracy greater than a single unit voxel, i.e. the distance between two adjoining nodes in graph space. Segmentation accuracy higher than a unit voxel is achievable by exploiting partial volume information in the voxels which shall result in non-equidistant spacing between adjoining graph nodes. This paper reports a generalized graph based multiple surface segmentation method with convex priors which can optimally segment the target surfaces in an irregularly sampled space. The proposed method allows non-equidistant spacing between the adjoining graph nodes to achieve subvoxel segmentation accuracy by utilizing the partial volume information in the voxels. The partial volume information in the voxels is exploited by computing a displacement field from the original volume data to identify the subvoxel-accurate centers within each voxel resulting in non-equidistant spacing between the adjoining graph nodes. The smoothness of each surface modeled as a convex constraint governs the connectivity and regularity of the surface. We employ an edge-based graph representation to incorporate the necessary constraints and the globally optimal solution is obtained by computing a minimum s-t cut. The proposed method was validated on 10 intravascular multi-frame ultrasound image datasets for subvoxel segmentation accuracy. In all cases, the approach yielded highly accurate results. Our approach can be readily extended to higher-dimensional segmentations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1611.03059](http://arxiv.org/abs/1611.03059)

##### PDF
[http://arxiv.org/pdf/1611.03059](http://arxiv.org/pdf/1611.03059)

