---
layout: post
title: "Dynamic Graph CNN for Learning on Point Clouds"
date: 2019-06-11 06:11:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Classification
author: Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon
mathjax: true
---

* content
{:toc}

##### Abstract
Point clouds provide a flexible geometric representation suitable for countless applications in computer graphics; they also comprise the raw output of most 3D data acquisition devices. While hand-designed features on point clouds have long been proposed in graphics and vision, however, the recent overwhelming success of convolutional neural networks (CNNs) for image analysis suggests the value of adapting insight from CNN to the point cloud world. Point clouds inherently lack topological information so designing a model to recover topology can enrich the representation power of point clouds. To this end, we propose a new neural network module dubbed EdgeConv suitable for CNN-based high-level tasks on point clouds including classification and segmentation. EdgeConv acts on graphs dynamically computed in each layer of the network. It is differentiable and can be plugged into existing architectures. Compared to existing modules operating in extrinsic space or treating each point independently, EdgeConv has several appealing properties: It incorporates local neighborhood information; it can be stacked applied to learn global shape properties; and in multi-layer systems affinity in feature space captures semantic characteristics over potentially long distances in the original embedding. We show the performance of our model on standard benchmarks including ModelNet40, ShapeNetPart, and S3DIS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.07829](http://arxiv.org/abs/1801.07829)

##### PDF
[http://arxiv.org/pdf/1801.07829](http://arxiv.org/pdf/1801.07829)

