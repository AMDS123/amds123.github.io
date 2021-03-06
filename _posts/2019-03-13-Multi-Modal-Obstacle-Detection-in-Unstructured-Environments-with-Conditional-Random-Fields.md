---
layout: post
title: "Multi-Modal Obstacle Detection in Unstructured Environments with Conditional Random Fields"
date: 2019-03-13 14:04:28
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Classification Detection
author: Mikkel Kragh, James Underwood
mathjax: true
---

* content
{:toc}

##### Abstract
Reliable obstacle detection and classification in rough and unstructured terrain such as agricultural fields or orchards remains a challenging problem. These environments involve large variations in both geometry and appearance, challenging perception systems that rely on only a single sensor modality. Geometrically, tall grass, fallen leaves, or terrain roughness can mistakenly be perceived as nontraversable or might even obscure actual obstacles. Likewise, traversable grass or dirt roads and obstacles such as trees and bushes might be visually ambiguous. In this paper, we combine appearance- and geometry-based detection methods by probabilistically fusing lidar and camera sensing with semantic segmentation using a conditional random field. We apply a state-of-the-art multimodal fusion algorithm from the scene analysis domain and adjust it for obstacle detection in agriculture with moving ground vehicles. This involves explicitly handling sparse point cloud data and exploiting both spatial, temporal, and multimodal links between corresponding 2D and 3D regions. The proposed method was evaluated on a diverse data set, comprising a dairy paddock and different orchards gathered with a perception research robot in Australia. Results showed that for a two-class classification problem (ground and nonground), only the camera leveraged from information provided by the other modality with an increase in the mean classification score of 0.5%. However, as more classes were introduced (ground, sky, vegetation, and object), both modalities complemented each other with improvements of 1.4% in 2D and 7.9% in 3D. Finally, introducing temporal links between successive frames resulted in improvements of 0.2% in 2D and 1.5% in 3D.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1706.02908](http://arxiv.org/abs/1706.02908)

##### PDF
[http://arxiv.org/pdf/1706.02908](http://arxiv.org/pdf/1706.02908)

