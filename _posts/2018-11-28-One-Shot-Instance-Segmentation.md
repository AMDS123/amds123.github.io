---
layout: post
title: "One-Shot Instance Segmentation"
date: 2018-11-28 11:36:21
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Detection
author: Claudio Michaelis, Ivan Ustyuzhaninov, Matthias Bethge, Alexander S. Ecker
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle one-shot visual search by example for arbitrary object categories: Given an example image of a novel reference object, find and segment all object instances of the same category within a scene. To address this problem, we propose Siamese Mask R-CNN. It extends Mask R-CNN by a Siamese backbone encoding both reference image and scene, allowing it to target detection and segmentation towards the reference category. We use Siamese Mask R-CNN to perform one-shot instance segmentation on MS-COCO, demonstrating that it can detect and segment objects of novel categories it was not trained on, and without using mask annotations at test time. Our results highlight challenges of the one-shot setting: while transferring knowledge about instance segmentation to novel object categories not used during training works very well, targeting the detection and segmentation networks towards the reference category appears to be more difficult. Our work provides a first strong baseline for one-shot instance segmentation and will hopefully inspire further research in this relatively unexplored field.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11507](http://arxiv.org/abs/1811.11507)

##### PDF
[http://arxiv.org/pdf/1811.11507](http://arxiv.org/pdf/1811.11507)

