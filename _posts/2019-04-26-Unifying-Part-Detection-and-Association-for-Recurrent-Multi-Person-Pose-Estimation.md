---
layout: post
title: "Unifying Part Detection and Association for Recurrent Multi-Person Pose Estimation"
date: 2019-04-26 14:22:07
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation RNN Detection
author: Rania Briq, Andreas Doering, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a joint model of human joint detection and association for 2D multi-person pose estimation (MPPE). The approach unifies training of joint detection and association without a need for further processing or sophisticated heuristics in order to associate the joints with people individually. The approach consists of two stages, where in the first stage joint detection heatmaps and association features are extracted, and in the second stage, whose input are the extracted features of the first stage, we introduce a recurrent neural network (RNN) which predicts the heatmaps of a single person's joints in each iteration. In addition, the network learns a stopping criterion in order to halt once it has identified all individuals in the image. This approach allowed us to eliminate several heuristic assumptions and parameters needed for association which do not necessarily hold true. Additionally, such an end-to-end approach allows the final objective to be known and directly optimized over during training. We evaluated our model on the challenging MSCOCO dataset and obtained an improvement over the baseline, particularly in challenging scenes with occlusions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11864](http://arxiv.org/abs/1904.11864)

##### PDF
[http://arxiv.org/pdf/1904.11864](http://arxiv.org/pdf/1904.11864)

