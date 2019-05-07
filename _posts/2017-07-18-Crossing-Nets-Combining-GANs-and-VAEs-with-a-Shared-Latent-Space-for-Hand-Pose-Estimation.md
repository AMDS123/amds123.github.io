---
layout: post
title: "Crossing Nets: Combining GANs and VAEs with a Shared Latent Space for Hand Pose Estimation"
date: 2017-07-18 18:30:33
categories: arXiv_CV
tags: arXiv_CV GAN Pose_Estimation Relation
author: Chengde Wan, Thomas Probst, Luc Van Gool, Angela Yao
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for 3D hand pose estimation from depth images require large amounts of annotated training data. We propose to model the statistical relationships of 3D hand poses and corresponding depth images using two deep generative models with a shared latent space. By design, our architecture allows for learning from unlabeled image data in a semi-supervised manner. Assuming a one-to-one mapping between a pose and a depth map, any given point in the shared latent space can be projected into both a hand pose and a corresponding depth map. Regressing the hand pose can then be done by learning a discriminator to estimate the posterior of the latent pose given some depth maps. To improve generalization and to better exploit unlabeled depth maps, we jointly train a generator and a discriminator. At each iteration, the generator is updated with the back-propagated gradient from the discriminator to synthesize realistic depth maps of the articulated hand, while the discriminator benefits from an augmented training set of synthesized and unlabeled samples. The proposed discriminator network architecture is highly efficient and runs at 90 FPS on the CPU with accuracies comparable or better than state-of-art on 3 publicly available benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1702.03431](https://arxiv.org/abs/1702.03431)

##### PDF
[https://arxiv.org/pdf/1702.03431](https://arxiv.org/pdf/1702.03431)

