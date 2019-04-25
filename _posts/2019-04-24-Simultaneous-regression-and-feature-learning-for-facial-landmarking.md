---
layout: post
title: "Simultaneous regression and feature learning for facial landmarking"
date: 2019-04-24 13:15:30
categories: arXiv_CV
tags: arXiv_CV Salient Face Tracking Classification Recognition
author: Janez Kri&#x17e;aj, Peter Peer, Vitomir &#x160;truc, Simon Dobri&#x161;ek
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment (or facial landmarking) is an important task in many face-related applications, ranging from registration, tracking and animation to higher-level classification problems such as face, expression or attribute recognition. While several solutions have been presented in the literature for this task so far, reliably locating salient facial features across a wide range of posses still remains challenging. To address this issue, we propose in this paper a novel method for automatic facial landmark localization in 3D face data designed specifically to address appearance variability caused by significant pose variations. Our method builds on recent cascaded-regression-based methods to facial landmarking and uses a gating mechanism to incorporate multiple linear cascaded regression models each trained for a limited range of poses into a single powerful landmarking model capable of processing arbitrary posed input data. We develop two distinct approaches around the proposed gating mechanism: i) the first uses a gated multiple ridge descent (GRID) mechanism in conjunction with established (hand-crafted) HOG features for face alignment and achieves state-of-the-art landmarking performance across a wide range of facial poses, ii) the second simultaneously learns multiple-descent directions as well as binary features (SMUF) that are optimal for the alignment tasks and in addition to competitive landmarking results also ensures extremely rapid processing. We evaluate both approaches in rigorous experiments on several popular datasets of 3D face images, i.e., the FRGCv2 and Bosphorus 3D Face datasets and image collections F and G from the University of Notre Dame. The results of our evaluation show that both approaches are competitive in comparison to the state-of-the-art, while exhibiting considerable robustness to pose variations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10787](http://arxiv.org/abs/1904.10787)

##### PDF
[http://arxiv.org/pdf/1904.10787](http://arxiv.org/pdf/1904.10787)

