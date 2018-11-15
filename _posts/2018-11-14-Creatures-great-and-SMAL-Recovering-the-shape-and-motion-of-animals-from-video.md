---
layout: post
title: "Creatures great and SMAL: Recovering the shape and motion of animals from video"
date: 2018-11-14 14:24:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Deep_Learning
author: Benjamin Biggs, Thomas Roddick, Andrew Fitzgibbon, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
We present a system to recover the 3D shape and motion of a wide variety of quadrupeds from video. The system comprises a machine learning front-end which predicts candidate 2D joint positions, a discrete optimization which finds kinematically plausible joint correspondences, and an energy minimization stage which fits a detailed 3D model to the image. In order to overcome the limited availability of motion capture training data from animals, and the difficulty of generating realistic synthetic training images, the system is designed to work on silhouette data. The joint candidate predictor is trained on synthetically generated silhouette images, and at test time, deep learning methods or standard video segmentation tools are used to extract silhouettes from real data. The system is tested on animal videos from several species, and shows accurate reconstructions of 3D shape and pose.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05804](http://arxiv.org/abs/1811.05804)

##### PDF
[http://arxiv.org/pdf/1811.05804](http://arxiv.org/pdf/1811.05804)

