---
layout: post
title: "Neural Rerendering in the Wild"
date: 2019-04-08 18:30:14
categories: arXiv_CV
tags: arXiv_CV
author: Moustafa Meshry, Dan B Goldman, Sameh Khamis, Hugues Hoppe, Rohit Pandey, Noah Snavely, Ricardo Martin-Brualla
mathjax: true
---

* content
{:toc}

##### Abstract
We explore total scene capture -- recording, modeling, and rerendering a scene under varying appearance such as season and time of day. Starting from internet photos of a tourist landmark, we apply traditional 3D reconstruction to register the photos and approximate the scene as a point cloud. For each photo, we render the scene points into a deep framebuffer, and train a neural network to learn the mapping of these initial renderings to the actual photos. This rerendering network also takes as input a latent appearance vector and a semantic mask indicating the location of transient objects like pedestrians. The model is evaluated on several datasets of publicly available images spanning a broad range of illumination conditions. We create short videos demonstrating realistic manipulation of the image viewpoint, appearance, and semantic labeling. We also compare results with prior work on scene reconstruction from internet photos.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04290](http://arxiv.org/abs/1904.04290)

##### PDF
[http://arxiv.org/pdf/1904.04290](http://arxiv.org/pdf/1904.04290)

