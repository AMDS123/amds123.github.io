---
layout: post
title: "Resolving Overlapping Convex Objects in Silhouette Images by Concavity Analysis and Gaussian Process"
date: 2019-06-03 19:55:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Sahar Zafari, Mariia Murashkina, Tuomas Eerola, Jouni Sampo, Heikki K&#xe4;lvi&#xe4;inen, Heikki Haario
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of overlapping convex objects has various applications, for example, in nanoparticles and cell imaging. Often the segmentation method has to rely purely on edges between the background and foreground making the analyzed images essentially silhouette images. Therefore, to segment the objects, the method needs to be able to resolve the overlaps between multiple objects by utilizing prior information about the shape of the objects. This paper introduces a novel method for segmentation of clustered partially overlapping convex objects in silhouette images. The proposed method involves three main steps: pre-processing, contour evidence extraction, and contour estimation. Contour evidence extraction starts by recovering contour segments from a binarized image by detecting concave points. After this, the contour segments which belong to the same objects are grouped. The grouping is formulated as a combinatorial optimization problem and solved using the branch and bound algorithm. Finally, the full contours of the objects are estimated by a Gaussian process regression method. The experiments on a challenging dataset consisting of nanoparticles demonstrate that the proposed method outperforms three current state-of-art approaches in overlapping convex objects segmentation. The method relies only on edge information and can be applied to any segmentation problems where the objects are partially overlapping and have a convex shape.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01049](http://arxiv.org/abs/1906.01049)

##### PDF
[http://arxiv.org/pdf/1906.01049](http://arxiv.org/pdf/1906.01049)

