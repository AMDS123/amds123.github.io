---
layout: post
title: "KPTransfer: improved performance and faster convergence from keypoint subset-wise domain transfer in human pose estimation"
date: 2019-03-24 05:26:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation Detection
author: Kanav Vats, Helmut Neher, Alexander Wong, David A. Clausi, John Zelek
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel approach called KPTransfer for improving modeling performance for keypoint detection deep neural networks via domain transfer between different keypoint subsets. This approach is motivated by the notion that rich contextual knowledge can be transferred between different keypoint subsets representing separate domains. In particular, the proposed method takes into account various keypoint subsets/domains by sequentially adding and removing keypoints. Contextual knowledge is transferred between two separate domains via domain transfer. Experiments to demonstrate the efficacy of the proposed KPTransfer approach were performed for the task of human pose estimation on the MPII dataset, with comparisons against random initialization and frozen weight extraction configurations. Experimental results demonstrate the efficacy of performing domain transfer between two different joint subsets resulting in a PCKh improvement of up to 1.1 over random initialization on joints such as wrists and knee in certain joint splits with an overall PCKh improvement of 0.5. Domain transfer from a different set of joints not only results in improved accuracy but also results in faster convergence because of mutual co-adaptations of weights resulting from the contextual knowledge of the pose from a different set of joints.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09926](http://arxiv.org/abs/1903.09926)

##### PDF
[http://arxiv.org/pdf/1903.09926](http://arxiv.org/pdf/1903.09926)

