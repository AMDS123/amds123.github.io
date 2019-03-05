---
layout: post
title: "Incremental Visual-Inertial 3D Mesh Generation with Structural Regularities"
date: 2019-03-04 04:24:50
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization
author: Antoni Rosinol, Torsten Sattler, Marc Pollefeys, Luca Carlone
mathjax: true
---

* content
{:toc}

##### Abstract
Visual-Inertial Odometry (VIO) algorithms typically rely on a point cloud representation of the scene that does not model the topology of the environment. A 3D mesh instead offers a richer, yet lightweight, model. Nevertheless, building a 3D mesh out of the sparse and noisy 3D landmarks triangulated by a VIO algorithm often results in a mesh that does not fit the real scene. In order to regularize the mesh, previous approaches decouple state estimation from the 3D mesh regularization step, and either limit the 3D mesh to the current frame or let the mesh grow indefinitely. We propose instead to tightly couple mesh regularization and state estimation by detecting and enforcing structural regularities in a novel factor-graph formulation. We also propose to incrementally build the mesh by restricting its extent to the time-horizon of the VIO optimization; the resulting 3D mesh covers a larger portion of the scene than a per-frame approach while its memory usage and computational complexity remain bounded. We show that our approach successfully regularizes the mesh, while improving localization accuracy, when structural regularities are present, and remains operational in scenes without regularities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01067](http://arxiv.org/abs/1903.01067)

##### PDF
[http://arxiv.org/pdf/1903.01067](http://arxiv.org/pdf/1903.01067)

