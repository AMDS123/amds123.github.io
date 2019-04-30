---
layout: post
title: "DeepHMap++: Combined Projection Grouping and Correspondence Learning for Full DoF Pose Estimation"
date: 2019-04-29 14:22:07
categories: arXiv_CV
tags: arXiv_CV Attention Pose_Estimation CNN
author: Mingliang Fu, Weijia Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, estimating the 6D pose of object instances with convolutional neural network (CNN) has received considerable attention. Depending on whether intermediate cues are used, the relevant literature can be roughly divided into two broad categories: direct methods and two stage pipelines. For the latter, intermediate cues, such as 3D object coordinates, semantic keypoints, or virtual control points instead of pose parameters are regressed by CNN in the first stage. Object pose can then be solved by correspondence constraints constructed with these intermediate cues. In this paper, we focus on the postprocessing of a two-stage pipeline and propose to combine two learning concepts for estimating object pose under challenging scenes: projection grouping on one side, and correspondence learning on the other. We firstly employ a local patch based method to predict projection heatmaps which denote the confidence distribution of projection of 3D bounding box's corners. A projection grouping module is then proposed to remove redundant local maxima from each layer of heatmaps. Instead of directly feeding 2D-3D correspondences to the perspective-n-point (PnP) algorithm, multiple correspondence hypotheses are sampled from local maxima and its corresponding neighborhood and ranked by a correspondence-evaluation network. Finally, correspondences with higher confidence are selected to determine object pose. Extensive experiments on three public datasets demonstrate that the proposed framework outperforms several state of the art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12735](http://arxiv.org/abs/1904.12735)

##### PDF
[http://arxiv.org/pdf/1904.12735](http://arxiv.org/pdf/1904.12735)

