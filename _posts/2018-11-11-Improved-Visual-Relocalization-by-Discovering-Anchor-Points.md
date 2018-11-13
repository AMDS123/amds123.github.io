---
layout: post
title: "Improved Visual Relocalization by Discovering Anchor Points"
date: 2018-11-11 08:39:57
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Multi_Task
author: Soham Saha, Girish Varma, C.V.Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
We address the visual relocalization problem of predicting the location and camera orientation or pose (6DOF) of the given input scene. We propose a method based on how humans determine their location using the visible landmarks. We define anchor points uniformly across the route map and propose a deep learning architecture which predicts the most relevant anchor point present in the scene as well as the relative offsets with respect to it. The relevant anchor point need not be the nearest anchor point to the ground truth location, as it might not be visible due to the pose. Hence we propose a multi task loss function, which discovers the relevant anchor point, without needing the ground truth for it. We validate the effectiveness of our approach by experimenting on CambridgeLandmarks (large scale outdoor scenes) as well as 7 Scenes (indoor scenes) using variousCNN feature extractors. Our method improves the median error in indoor as well as outdoor localization datasets compared to the previous best deep learning model known as PoseNet (with geometric re-projection loss) using the same feature extractor. We improve the median error in localization in the specific case of Street scene, by over 8m.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04370](http://arxiv.org/abs/1811.04370)

##### PDF
[http://arxiv.org/pdf/1811.04370](http://arxiv.org/pdf/1811.04370)

