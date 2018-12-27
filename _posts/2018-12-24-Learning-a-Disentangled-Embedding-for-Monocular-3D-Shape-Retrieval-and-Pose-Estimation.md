---
layout: post
title: "Learning a Disentangled Embedding for Monocular 3D Shape Retrieval and Pose Estimation"
date: 2018-12-24 11:44:36
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Embedding
author: Kyaw Zaw Lin, Weipeng Xu, Qianru Sun, Christian Theobalt, Tat-Seng Chua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach to jointly perform 3D object retrieval and pose estimation from monocular images.In order to make the method robust to real world scene variations in the images, e.g. texture, lighting and background,we learn an embedding space from 3D data that only includes the relevant information, namely the shape and pose.Our method can then be trained for robustness under real world scene variations without having to render a large training set simulating these variations. Our learned embedding explicitly disentangles a shape vector and a pose vector, which alleviates both pose bias for 3D shape retrieval and categorical bias for pose estimation. Having the learned disentangled embedding, we train a CNN to map the images to the embedding space, and then retrieve the closest 3D shape from the database and estimate the 6D pose of the object using the embedding vectors. Our method achieves 10.8 median error for pose estimation and 0.514 top-1-accuracy for category agnostic 3D object retrieval on the Pascal3D+ dataset. It therefore outperforms the previous state-of-the-art methods on both tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09899](http://arxiv.org/abs/1812.09899)

##### PDF
[http://arxiv.org/pdf/1812.09899](http://arxiv.org/pdf/1812.09899)

