---
layout: post
title: "Modeling Human Motion with Quaternion-based Neural Networks"
date: 2019-01-21 23:56:54
categories: arXiv_AI
tags: arXiv_AI CNN Prediction
author: Dario Pavllo, Christoph Feichtenhofer, Michael Auli, David Grangier
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work on predicting or generating 3D human pose sequences regresses either joint rotations or joint positions. The former strategy is prone to error accumulation along the kinematic chain, as well as discontinuities when using Euler angles or exponential maps as parameterizations. The latter requires re-projection onto skeleton constraints to avoid bone stretching and invalid configurations. This work addresses both limitations. QuaterNet represents rotations with quaternions and our loss function performs forward kinematics on a skeleton to penalize absolute position errors instead of angle errors. We investigate both recurrent and convolutional architectures and evaluate on short-term prediction and long-term generation. For the latter, our approach is qualitatively judged as realistic as recent neural strategies from the graphics literature. Our experiments compare quaternions to Euler angles as well as exponential maps and show that only a very short context is required to make reliable future predictions. Finally, we show that the standard evaluation protocol for Human3.6M produces high variance results and we propose a simple solution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07677](http://arxiv.org/abs/1901.07677)

##### PDF
[http://arxiv.org/pdf/1901.07677](http://arxiv.org/pdf/1901.07677)

