---
layout: post
title: "Structure-Aware 3D Hourglass Network for Hand Pose Estimation from Single Depth Image"
date: 2018-12-26 14:08:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Fuyang Huang, Ailing Zeng, Minhao Liu, Jing Qin, Qiang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel structure-aware 3D hourglass network for hand pose estimation from a single depth image, which achieves state-of-the-art results on MSRA and NYU datasets. Compared to existing works that perform image-to-coordination regression, our network takes 3D voxel as input and directly regresses 3D heatmap for each joint. To be specific, we use hourglass network as our backbone network and modify it into 3D form. We explicitly model tree-like finger bone into the network as well as in the loss function in an end-to-end manner, in order to take the skeleton constraints into consideration. Final estimation can then be easily obtained from voxel density map with simple post-processing. Experimental results show that the proposed structure-aware 3D hourglass network is able to achieve a mean joint error of 7.4 mm in MSRA and 8.9 mm in NYU datasets, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10320](http://arxiv.org/abs/1812.10320)

##### PDF
[http://arxiv.org/pdf/1812.10320](http://arxiv.org/pdf/1812.10320)

