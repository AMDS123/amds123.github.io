---
layout: post
title: "Learning to Estimate Pose and Shape of Hand-Held Objects from RGB Images"
date: 2019-03-08 09:40:51
categories: arXiv_CV
tags: arXiv_CV GAN CNN Inference Quantitative
author: Mia Kokic, Danica Kragic, Jeannette Bohg
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a system for modeling hand-object interactions in 3D from RGB images that show a hand which is holding a novel object from a known category. We design a Convolutional Neural Network (CNN) for Hand-held Object Pose and Shape estimation called HOPS-Net and utilize prior work to estimate the hand pose and configuration. We leverage the insight that information about the hand facilitates object pose and shape estimation by incorporating the hand into both training and inference of the object pose and shape as well as the refinement of the estimated pose. The network is trained on a large synthetic dataset of objects in interaction with a human hand. To bridge the gap between real and synthetic images, we employ an image-to-image translation model (Augmented CycleGAN) that generates realistically textured objects given a synthetic rendering. This provides a scalable way of generating annotated data for training HOPS-Net. Our quantitative experiments show that even noisy hand parameters significantly help object pose and shape estimation. The qualitative experiments show results of pose and shape estimation of objects held by a hand "in the wild".

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03340](http://arxiv.org/abs/1903.03340)

##### PDF
[http://arxiv.org/pdf/1903.03340](http://arxiv.org/pdf/1903.03340)

