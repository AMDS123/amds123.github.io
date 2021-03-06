---
layout: post
title: "Recovery of Superquadrics from Range Images using Deep Learning: A Preliminary Study"
date: 2019-04-13 19:01:11
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Tim Oblak, Klemen Grm, Ale&#x161; Jakli&#x10d;, Peter Peer, Vitomir &#x160;truc, Franc Solina
mathjax: true
---

* content
{:toc}

##### Abstract
It has been a longstanding goal in computer vision to describe the 3D physical space in terms of parameterized volumetric models that would allow autonomous machines to understand and interact with their surroundings. Such models are typically motivated by human visual perception and aim to represents all elements of the physical word ranging from individual objects to complex scenes using a small set of parameters. One of the de facto stadards to approach this problem are superquadrics - volumetric models that define various 3D shape primitives and can be fitted to actual 3D data (either in the form of point clouds or range images). However, existing solutions to superquadric recovery involve costly iterative fitting procedures, which limit the applicability of such techniques in practice. To alleviate this problem, we explore in this paper the possibility to recover superquadrics from range images without time consuming iterative parameter estimation techniques by using contemporary deep-learning models, more specifically, convolutional neural networks (CNNs). We pose the superquadric recovery problem as a regression task and develop a CNN regressor that is able to estimate the parameters of a superquadric model from a given range image. We train the regressor on a large set of synthetic range images, each containing a single (unrotated) superquadric shape and evaluate the learned model in comparaitve experiments with the current state-of-the-art. Additionally, we also present a qualitative analysis involving a dataset of real-world objects. The results of our experiments show that the proposed regressor not only outperforms the existing state-of-the-art, but also ensures a 270x faster execution time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06585](http://arxiv.org/abs/1904.06585)

##### PDF
[http://arxiv.org/pdf/1904.06585](http://arxiv.org/pdf/1904.06585)

