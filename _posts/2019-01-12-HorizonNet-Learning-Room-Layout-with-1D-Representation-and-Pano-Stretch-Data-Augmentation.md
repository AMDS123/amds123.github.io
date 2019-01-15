---
layout: post
title: "HorizonNet: Learning Room Layout with 1D Representation and Pano Stretch Data Augmentation"
date: 2019-01-12 13:57:29
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Cheng Sun, Chi-Wei Hsiao, Min Sun, Hwann-Tzong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach to the problem of estimating 3D room layout from a single panoramic image. We represent room layout as three 1D vectors that encode, at each image column, the boundary positions of floor-wall and ceiling-wall, and the existence of wall-wall boundary. The proposed network architecture, HorizonNet, trained for predicting 1D layout, outperforms previous state-of-the-art approaches. The designed post-processing procedure for recovering 3D room layouts from 1D predictions can automatically infer the room shape with low computation cost---it takes less than 20ms for a panorama image while prior works might need dozens of seconds. We also propose Pano Stretch Data Augmentation, which can diversify panorama data and be applied to other panorama-related learning tasks. Due to the limited training data available for non-cuboid layout, we re-annotate 65 general layout data from the current dataset for fine-tuning and qualitatively show the ability of our approach to estimate general layouts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03861](http://arxiv.org/abs/1901.03861)

##### PDF
[http://arxiv.org/pdf/1901.03861](http://arxiv.org/pdf/1901.03861)

