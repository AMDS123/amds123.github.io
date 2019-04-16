---
layout: post
title: "Bounce and Learn: Modeling Scene Dynamics with Real-World Bounces"
date: 2019-04-15 03:31:31
categories: arXiv_CV
tags: arXiv_CV Face Inference Prediction
author: Senthil Purushwalkam, Abhinav Gupta, Danny M. Kaufman, Bryan Russell
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an approach to model surface properties governing bounces in everyday scenes. Our model learns end-to-end, starting from sensor inputs, to predict post-bounce trajectories and infer two underlying physical properties that govern bouncing - restitution and effective collision normals. Our model, Bounce and Learn, comprises two modules -- a Physics Inference Module (PIM) and a Visual Inference Module (VIM). VIM learns to infer physical parameters for locations in a scene given a single still image, while PIM learns to model physical interactions for the prediction task given physical parameters and observed pre-collision 3D trajectories. To achieve our results, we introduce the Bounce Dataset comprising 5K RGB-D videos of bouncing trajectories of a foam ball to probe surfaces of varying shapes and materials in everyday scenes including homes and offices. Our proposed model learns from our collected dataset of real-world bounces and is bootstrapped with additional information from simple physics simulations. We show on our newly collected dataset that our model out-performs baselines, including trajectory fitting with Newtonian physics, in predicting post-bounce trajectories and inferring physical properties of a scene.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06827](http://arxiv.org/abs/1904.06827)

##### PDF
[http://arxiv.org/pdf/1904.06827](http://arxiv.org/pdf/1904.06827)

