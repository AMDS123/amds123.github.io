---
layout: post
title: "Multiple Instance Curriculum Learning for Weakly Supervised Object Detection"
date: 2017-11-25 05:08:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Face Detection
author: Siyang Li, Xiangxin Zhu, Qin Huang, Hao Xu, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
When supervising an object detector with weakly labeled data, most existing approaches are prone to trapping in the discriminative object parts, e.g., finding the face of a cat instead of the full body, due to lacking the supervision on the extent of full objects. To address this challenge, we incorporate object segmentation into the detector training, which guides the model to correctly localize the full objects. We propose the multiple instance curriculum learning (MICL) method, which injects curriculum learning (CL) into the multiple instance learning (MIL) framework. The MICL method starts by automatically picking the easy training examples, where the extent of the segmentation masks agree with detection bounding boxes. The training set is gradually expanded to include harder examples to train strong detectors that handle complex images. The proposed MICL method with segmentation in the loop outperforms the state-of-the-art weakly supervised object detectors by a substantial margin on the PASCAL VOC datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.09191](https://arxiv.org/abs/1711.09191)

##### PDF
[https://arxiv.org/pdf/1711.09191](https://arxiv.org/pdf/1711.09191)

