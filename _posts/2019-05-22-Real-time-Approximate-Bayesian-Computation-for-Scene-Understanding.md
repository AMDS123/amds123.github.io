---
layout: post
title: "Real-time Approximate Bayesian Computation for Scene Understanding"
date: 2019-05-22 20:03:13
categories: arXiv_CV
tags: arXiv_CV Inference
author: Javier Felip, Nilesh Ahuja, David G&#xf3;mez-Guti&#xe9;rrez, Omesh Tickoo, Vikash Mansinghka
mathjax: true
---

* content
{:toc}

##### Abstract
Consider scene understanding problems such as predicting where a person is probably reaching, or inferring the pose of 3D objects from depth images, or inferring the probable street crossings of pedestrians at a busy intersection. This paper shows how to solve these problems using Approximate Bayesian Computation. The underlying generative models are built from realistic simulation software, wrapped in a Bayesian error model for the gap between simulation outputs and real data. The simulators are drawn from off-the-shelf computer graphics, video game, and traffic simulation code. The paper introduces two techniques for speeding up inference that can be used separately or in combination. The first is to train neural surrogates of the simulators, using a simple form of domain randomization to make the surrogates more robust to the gap between the simulation and reality. The second is to adaptively discretize the latent variables using a Tree-pyramid approach adapted from computer graphics. This paper also shows performance and accuracy measurements on real-world problems, establishing that it is feasible to solve these problems in real-time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13307](http://arxiv.org/abs/1905.13307)

##### PDF
[http://arxiv.org/pdf/1905.13307](http://arxiv.org/pdf/1905.13307)

