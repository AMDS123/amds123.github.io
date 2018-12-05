---
layout: post
title: "Cross-Classification Clustering: An Efficient Multi-Object Tracking Technique for 3-D Instance Segmentation in Connectomics"
date: 2018-12-04 01:18:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Classification
author: Yaron Meirovitch, Lu Mi, Hayk Saribekyan, Alexander Matveev, David Rolnick, Casimir Wierzynski, Nir Shavit
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-accurate tracking of objects is a key element in many computer vision applications, often solved by iterated individual object tracking or instance segmentation followed by object matching. Here we introduce cross-classification clustering (3C), a new technique that simultaneously tracks all objects in an image stack. The key idea in cross-classification is to efficiently turn a clustering problem into a classification problem by running a logarithmic number of independent classifications, letting the cross-labeling of these classifications uniquely classify each pixel to the object labels. We apply the 3C mechanism to achieve state-of-the-art accuracy in connectomics - nanoscale mapping of the brain from electron microscopy volumes. Our reconstruction system introduces an order of magnitude scalability improvement over the best current methods for neuronal reconstruction, and can be seamlessly integrated within existing single-object tracking methods like Google's flood-filling networks to improve their performance. This scalability is crucial for the real-world deployment of connectomics pipelines, as the best performing existing techniques require computing infrastructures that are beyond the reach of most labs. We believe 3C has valuable scalability implications in other domains that require pixel-accurate tracking of multiple objects in image stacks or video.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01157](http://arxiv.org/abs/1812.01157)

##### PDF
[http://arxiv.org/pdf/1812.01157](http://arxiv.org/pdf/1812.01157)

