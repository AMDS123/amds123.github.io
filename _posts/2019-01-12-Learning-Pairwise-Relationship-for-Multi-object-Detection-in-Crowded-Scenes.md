---
layout: post
title: "Learning Pairwise Relationship for Multi-object Detection in Crowded Scenes"
date: 2019-01-12 04:43:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Deep_Learning Detection Relation
author: Yu Liu, Lingqiao Liu, Hamid Rezatofighi, Thanh-Toan Do, Qinfeng Shi, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
As the post-processing step for object detection, non-maximum suppression (GreedyNMS) is widely used in most of the detectors for many years. It is efficient and accurate for sparse scenes, but suffers an inevitable trade-off between precision and recall in crowded scenes. To overcome this drawback, we propose a Pairwise-NMS to cure GreedyNMS. Specifically, a pairwise-relationship network that is based on deep learning is learned to predict if two overlapping proposal boxes contain two objects or zero/one object, which can handle multiple overlapping objects effectively. Through neatly coupling with GreedyNMS without losing efficiency, consistent improvements have been achieved in heavily occluded datasets including MOT15, TUD-Crossing and PETS. In addition, Pairwise-NMS can be integrated into any learning based detectors (Both of Faster-RCNN and DPM detectors are tested in this paper), thus building a bridge between GreedyNMS and end-to-end learning detectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03796](http://arxiv.org/abs/1901.03796)

##### PDF
[http://arxiv.org/pdf/1901.03796](http://arxiv.org/pdf/1901.03796)

