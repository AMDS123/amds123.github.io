---
layout: post
title: "LCR-Net++: Multi-person 2D and 3D Pose Detection in Natural Images"
date: 2019-01-13 19:33:24
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Classification Detection
author: Gregory Rogez, Philippe Weinzaepfel, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end architecture for joint 2D and 3D human pose estimation in natural images. Key to our approach is the generation and scoring of a number of pose proposals per image, which allows us to predict 2D and 3D poses of multiple people simultaneously. Hence, our approach does not require an approximate localization of the humans for initialization. Our Localization-Classification-Regression architecture, named LCR-Net, contains 3 main components: 1) the pose proposal generator that suggests candidate poses at different locations in the image; 2) a classifier that scores the different pose proposals; and 3) a regressor that refines pose proposals both in 2D and 3D. All three stages share the convolutional feature layers and are trained jointly. The final pose estimation is obtained by integrating over neighboring pose hypotheses, which is shown to improve over a standard non maximum suppression algorithm. Our method recovers full-body 2D and 3D poses, hallucinating plausible body parts when the persons are partially occluded or truncated by the image boundary. Our approach significantly outperforms the state of the art in 3D pose estimation on Human3.6M, a controlled environment. Moreover, it shows promising results on real images for both single and multi-person subsets of the MPII 2D pose benchmark and demonstrates satisfying 3D pose results even for multi-person images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.00455](http://arxiv.org/abs/1803.00455)

##### PDF
[http://arxiv.org/pdf/1803.00455](http://arxiv.org/pdf/1803.00455)

