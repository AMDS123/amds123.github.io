---
layout: post
title: "Multi-path Learning for Object Pose Estimation Across Domains"
date: 2019-08-01 00:01:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Martin Sundermeyer, Maximilian Durner, En Yen Puang, Zoltan-Csaba Marton, Rudolph Triebel
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a scalable approach for object pose estimation trained on simulated RGB views of multiple 3D models together. We learn an encoding of object views that does not only describe the orientation of all objects seen during training, but can also relate views of untrained objects. Our single-encoder-multi-decoder network is trained using a technique we denote "multi-path learning": While the encoder is shared by all objects, each decoder only reconstructs views of a single object. Consequently, views of different instances do not need to be separated in the latent space and can share common features. The resulting encoder generalizes well from synthetic to real data and across various instances, categories, model types and datasets. We systematically investigate the learned encodings, their generalization capabilities and iterative refinement strategies on the ModelNet40 and T-LESS dataset. On T-LESS, we achieve state-of-the-art results with our 6D Object Detection pipeline, both in the RGB and depth domain, outperforming learning-free pipelines at much lower runtimes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00151](http://arxiv.org/abs/1908.00151)

##### PDF
[http://arxiv.org/pdf/1908.00151](http://arxiv.org/pdf/1908.00151)

