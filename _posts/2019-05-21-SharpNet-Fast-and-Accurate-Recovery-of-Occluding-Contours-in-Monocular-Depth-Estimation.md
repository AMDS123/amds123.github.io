---
layout: post
title: "SharpNet: Fast and Accurate Recovery of Occluding Contours in Monocular Depth Estimation"
date: 2019-05-21 13:08:52
categories: arXiv_CV
tags: arXiv_CV Attention Prediction Recognition
author: Micha&#xeb;l Ramamonjisoa, Vincent Lepetit
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce SharpNet, a method that predicts an accurate depth map for an input color image, with a particular attention to the reconstruction of occluding contours: Occluding contours are an important cue for object recognition, and for realistic integration of virtual objects in Augmented Reality, but they are also notoriously difficult to reconstruct accurately. For example, they are a challenge for stereo-based reconstruction methods, as points around an occluding contour are visible in only one image. Inspired by recent methods that introduce normal estimation to improve depth prediction, we introduce a novel term that constrains depth and occluding contours predictions. Since ground truth depth is difficult to obtain with pixel-perfect accuracy along occluding contours, we use synthetic images for training, followed by fine-tuning on real data. We demonstrate our approach on the challenging NYUv2-Depth dataset, and show that our method outperforms the state-of-the-art along occluding contours, while performing on par with the best recent methods for the rest of the images. Its accuracy along the occluding contours is actually better than the `ground truth' acquired by a depth camera based on structured light. We show this by introducing a new benchmark based on NYUv2-Depth for evaluating occluding contours in monocular reconstruction, which is our second contribution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08598](http://arxiv.org/abs/1905.08598)

##### PDF
[http://arxiv.org/pdf/1905.08598](http://arxiv.org/pdf/1905.08598)

