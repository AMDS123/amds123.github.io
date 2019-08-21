---
layout: post
title: "Pix2Pose: Pixel-Wise Coordinate Regression of Objects for 6D Pose Estimation"
date: 2019-08-20 15:34:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Pose_Estimation Prediction
author: Kiru Park, Timothy Patten, Markus Vincze
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the 6D pose of objects using only RGB images remains challenging because of problems such as occlusion and symmetries. It is also difficult to construct 3D models with precise texture without expert knowledge or specialized scanning devices. To address these problems, we propose a novel pose estimation method, Pix2Pose, that predicts the 3D coordinates of each object pixel without textured models. An auto-encoder architecture is designed to estimate the 3D coordinates and expected errors per pixel. These pixel-wise predictions are then used in multiple stages to form 2D-3D correspondences to directly compute poses with the PnP algorithm with RANSAC iterations. Our method is robust to occlusion by leveraging recent achievements in generative adversarial training to precisely recover occluded parts. Furthermore, a novel loss function, the transformer loss, is proposed to handle symmetric objects by guiding predictions to the closest symmetric pose. Evaluations on three different benchmark datasets containing symmetric and occluded objects show our method outperforms the state of the art using only RGB images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07433](http://arxiv.org/abs/1908.07433)

##### PDF
[http://arxiv.org/pdf/1908.07433](http://arxiv.org/pdf/1908.07433)

