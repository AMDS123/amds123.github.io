---
layout: post
title: "Learning Robust 3D Face Reconstruction and Discriminative Identity Representation"
date: 2019-05-16 02:31:34
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Yao Luo, Xiaoguang Tu, Mei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
3D face reconstruction from a single 2D image is a very important topic in computer vision. However, the current reconstruction methods are usually non-sensitive to face identities and over-sensitive to facial poses, which may result in similar 3D geometries for faces of different identities, or obtain different shapes for the same identity with different poses. When such methods are applied practically, their 3D estimates are either changeable for different photos of the same subject or over-regularized and generic to distinguish face identities. In this paper, we propose a robust solution to solve this problem by carefully designing a novel Siamese Convolutional Neural Network (SCNN). Specifically, regarding the 3D Morphable face Model (3DMM) parameters of the same individual as the same class, we employ the contrastive loss to enlarge the inter-class distance and meanwhile reduce the intra-class distance for the output 3DMM parameters. We also propose an identity loss to preserve the identity information for the same individual in the feature space. Training with these two losses, our SCNN could learn representations that are more discriminative for face identity and generalizable for pose variants. Experiments on the challenging database 300W-LP and AFLW2000-3D have shown the effectiveness of our method by comparing with state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06505](http://arxiv.org/abs/1905.06505)

##### PDF
[http://arxiv.org/pdf/1905.06505](http://arxiv.org/pdf/1905.06505)

