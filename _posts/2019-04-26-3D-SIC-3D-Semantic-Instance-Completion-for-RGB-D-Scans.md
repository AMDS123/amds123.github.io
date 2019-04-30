---
layout: post
title: "3D-SIC: 3D Semantic Instance Completion for RGB-D Scans"
date: 2019-04-26 18:33:34
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Segmentation CNN Inference
author: Ji Hou, Angela Dai, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on the task of semantic instance completion: from an incomplete, RGB-D scan of a scene, we aim to detect the individual object instances comprising the scene and jointly infer their complete object geometry. This enables a semantically meaningful decomposition of a scanned scene into individual, complete 3D objects. This semantic instance completion of a 3D scene opens up many new possibilities in enabling meaningful interactions with a scene, for instance for virtual or robotic agents. Rather than considering 3D semantic instance segmentation and scan completion separately, we propose 3D-SIC, a new end-to-end 3D convolutional neural network which jointly learns to detect object instances and predict their complete geometry -- achieving significantly better performance than treating these tasks independently. 3D-SIC leverages joint color-geometry feature learning and a fully-convolutional 3D network to effectively infer semantic instance completion for 3D scans at scale. Our method runs at interactive rates, taking several seconds inference time on scenes of $30$m $\times$ $25$m spatial extent. For the task of semantic instance completion, we additionally introduce a new semantic instance completion benchmark on real scan data, where we outperform alternative approaches by over 15 in mAP@0.5.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12012](http://arxiv.org/abs/1904.12012)

##### PDF
[http://arxiv.org/pdf/1904.12012](http://arxiv.org/pdf/1904.12012)

