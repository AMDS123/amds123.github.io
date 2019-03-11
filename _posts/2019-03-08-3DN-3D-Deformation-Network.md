---
layout: post
title: "3DN: 3D Deformation Network"
date: 2019-03-08 08:35:48
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Weiyue Wang, Duygu Ceylan, Radomir Mech, Ulrich Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Applications in virtual and augmented reality create a demand for rapid creation and easy access to large sets of 3D models. An effective way to address this demand is to edit or deform existing 3D models based on a reference, e.g., a 2D image which is very easy to acquire. Given such a source 3D model and a target which can be a 2D image, 3D model, or a point cloud acquired as a depth scan, we introduce 3DN, an end-to-end network that deforms the source model to resemble the target. Our method infers per-vertex offset displacements while keeping the mesh connectivity of the source model fixed. We present a training strategy which uses a novel differentiable operation, mesh sampling operator, to generalize our method across source and target models with varying mesh densities. Mesh sampling operator can be seamlessly integrated into the network to handle meshes with different topologies. Qualitative and quantitative results show that our method generates higher quality results compared to the state-of-the art learning-based methods for 3D shape generation. Code is available at github.com/laughtervv/3DN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03322](http://arxiv.org/abs/1903.03322)

##### PDF
[http://arxiv.org/pdf/1903.03322](http://arxiv.org/pdf/1903.03322)

