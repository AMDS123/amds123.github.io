---
layout: post
title: "Learning to Regress 3D Face Shape and Expression from an Image without 3D Supervision"
date: 2019-05-16 14:57:45
categories: arXiv_CV
tags: arXiv_CV Face
author: Soubhik Sanyal, Timo Bolkart, Haiwen Feng, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
The estimation of 3D face shape from a single image must be robust to variations in lighting, head pose, expression, facial hair, makeup, and occlusions. Robustness requires a large training set of in-the-wild images, which by construction, lack ground truth 3D shape. To train a network without any 2D-to-3D supervision, we present RingNet, which learns to compute 3D face shape from a single image. Our key observation is that an individual's face shape is constant across images, regardless of expression, pose, lighting, etc. RingNet leverages multiple images of a person and automatically detected 2D face features. It uses a novel loss that encourages the face shape to be similar when the identity is the same and different for different people. We achieve invariance to expression by representing the face using the FLAME model. Once trained, our method takes a single image and outputs the parameters of FLAME, which can be readily animated. Additionally we create a new database of faces `not quite in-the-wild' (NoW) with 3D head scans and high-resolution images of the subjects in a wide variety of conditions. We evaluate publicly available methods and find that RingNet is more accurate than methods that use 3D supervision. The dataset, model, and results are available for research purposes at <a href="http://ringnet.is.tuebingen.mpg.de.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06817](http://arxiv.org/abs/1905.06817)

##### PDF
[http://arxiv.org/pdf/1905.06817](http://arxiv.org/pdf/1905.06817)

