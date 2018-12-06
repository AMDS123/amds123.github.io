---
layout: post
title: "Multiview Cross-supervision for Semantic Segmentation"
date: 2018-12-04 22:57:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Yuan Yao, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a semi-supervised learning framework for a customized semantic segmentation task using multiview image streams. A key challenge of the customized task lies in the limited accessibility of the labeled data due to the requirement of prohibitive manual annotation effort. We hypothesize that it is possible to leverage multiview image streams that are linked through the underlying 3D geometry, which can provide an additional supervisionary signal to train a segmentation model. We formulate a new cross-supervision method using a shape belief transfer---the segmentation belief in one image is used to predict that of the other image through epipolar geometry analogous to shape-from-silhouette. The shape belief transfer provides the upper and lower bounds of the segmentation for the unlabeled data where its gap approaches asymptotically to zero as the number of the labeled views increases. We integrate this theory to design a novel network that is agnostic to camera calibration, network model, and semantic category and bypasses the intermediate process of suboptimal 3D reconstruction. We validate this network by recognizing a customized semantic category per pixel from realworld visual data including non-human species and a subject of interest in social videos where attaining large-scale annotation data is infeasible.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01738](http://arxiv.org/abs/1812.01738)

##### PDF
[http://arxiv.org/pdf/1812.01738](http://arxiv.org/pdf/1812.01738)

