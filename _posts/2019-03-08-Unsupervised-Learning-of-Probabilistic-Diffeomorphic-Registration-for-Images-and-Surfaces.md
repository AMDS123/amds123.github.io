---
layout: post
title: "Unsupervised Learning of Probabilistic Diffeomorphic Registration for Images and Surfaces"
date: 2019-03-08 16:48:41
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Inference
author: Adrian V. Dalca, Guha Balakrishnan, John Guttag, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
Classical deformable registration techniques achieve impressive results and offer a rigorous theoretical treatment, but are computationally intensive since they solve an optimization problem for each image pair. Recently, learning-based methods have facilitated fast registration by learning spatial deformation functions. However, these approaches use restricted deformation models, require supervised labels, or do not guarantee a diffeomorphic (topology-preserving) registration. Furthermore, learning-based registration tools have not been derived from a probabilistic framework that can offer uncertainty estimates. 
 In this paper, we build a connection between classical and learning-based methods. We present a probabilistic generative model and derive an unsupervised learning-based inference algorithm that uses insights from classical registration methods and makes use of recent developments in convolutional neural networks (CNNs). We demonstrate our method on a 3D brain registration task for both images and anatomical surfaces, and provide extensive empirical analyses of the algorithm. Our principled approach results in state of the art accuracy and very fast runtimes, while providing diffeomorphic guarantees. Our implementation is available online at <a href="http://voxelmorph.csail.mit.edu.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03545](http://arxiv.org/abs/1903.03545)

##### PDF
[http://arxiv.org/pdf/1903.03545](http://arxiv.org/pdf/1903.03545)

