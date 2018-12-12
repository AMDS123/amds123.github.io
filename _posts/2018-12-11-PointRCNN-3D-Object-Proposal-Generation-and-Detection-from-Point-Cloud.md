---
layout: post
title: "PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud"
date: 2018-12-11 07:27:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Shaoshuai Shi, Xiaogang Wang, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose PointRCNN for 3D object detection from raw point cloud. The whole framework is composed of two stages: stage-1 for the bottom-up 3D proposal generation and stage-2 for refining proposals in the canonical coordinates to obtain the final detection results. Instead of generating proposals from RGB image or projecting point cloud to bird's view or voxels as previous methods do, our stage-1 sub-network directly generates a small number of high-quality 3D proposals from point cloud in a bottom-up manner via segmenting the point cloud of whole scene into foreground points and background. The stage-2 sub-network transforms the pooled points of each proposal to canonical coordinates to learn better local spatial features, which is combined with global semantic features of each point learned in stage-1 for accurate box refinement and confidence prediction. Extensive experiments on the 3D detection benchmark of KITTI dataset show that our proposed architecture outperforms state-of-the-art methods with remarkable margins by using only point cloud as input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04244](http://arxiv.org/abs/1812.04244)

##### PDF
[http://arxiv.org/pdf/1812.04244](http://arxiv.org/pdf/1812.04244)

