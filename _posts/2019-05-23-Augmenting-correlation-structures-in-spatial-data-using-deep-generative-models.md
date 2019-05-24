---
layout: post
title: "Augmenting correlation structures in spatial data using deep generative models"
date: 2019-05-23 17:39:23
categories: arXiv_AI
tags: arXiv_AI Sparse GAN Deep_Learning Prediction Relation
author: Konstantin Klemmer, Adriano Koshiyama, Sebastian Flennerhag
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art deep learning methods have shown a remarkable capacity to model complex data domains, but struggle with geospatial data. In this paper, we introduce SpaceGAN, a novel generative model for geospatial domains that learns neighbourhood structures through spatial conditioning. We propose to enhance spatial representation beyond mere spatial coordinates, by conditioning each data point on feature vectors of its spatial neighbours, thus allowing for a more flexible representation of the spatial structure. To overcome issues of training convergence, we employ a metric capturing the loss in local spatial autocorrelation between real and generated data as stopping criterion for SpaceGAN parametrization. This way, we ensure that the generator produces synthetic samples faithful to the spatial patterns observed in the input. SpaceGAN is successfully applied for data augmentation and outperforms compared to other methods of synthetic spatial data generation. Finally, we propose an ensemble learning framework for the geospatial domain, taking augmented SpaceGAN samples as training data for a set of ensemble learners. We empirically show the superiority of this approach over conventional ensemble learning approaches and rivaling spatial data augmentation methods, using synthetic and real-world prediction tasks. Our findings suggest that SpaceGAN can be used as a tool for (1) artificially inflating sparse geospatial data and (2) improving generalization of geospatial models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09796](http://arxiv.org/abs/1905.09796)

##### PDF
[http://arxiv.org/pdf/1905.09796](http://arxiv.org/pdf/1905.09796)

