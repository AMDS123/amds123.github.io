---
layout: post
title: "Render4Completion: Synthesizing Multi-view Depth Maps for 3D Shape Completion"
date: 2019-04-17 17:07:47
categories: arXiv_CV
tags: arXiv_CV
author: Tao Hu, Zhizhong Han, Abhinav Shrivastava, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach for 3D shape completion by synthesizing multi-view depth maps. While previous work for shape completion relies on volumetric representations, meshes, or point clouds, we propose to use multi-view depth maps from a set of fixed viewing angles as our shape representation. This allows us to be free of the limitations of memory for volumetric representations and point clouds by casting shape completion into an image-to-image translation problem. Specifically, we render depth maps of the incomplete shape from a fixed set of viewpoints, and perform depth map completion in each view. Different from image-to-image translation network that completes each view separately, our novel network, multi-view completion net (MVCN), leverages information from all views of a 3D shape to help the completion of each single view. This enables MVCN to leverage more information from different depth views to achieve high accuracy in single depth view completion and keep the consistency among the completed depth images in different views. Benefited by the multi-view representation and the novel network structure, MVCN significantly improves the accuracy of 3D shape completion in large-scale benchmarks compared to the state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08366](http://arxiv.org/abs/1904.08366)

##### PDF
[http://arxiv.org/pdf/1904.08366](http://arxiv.org/pdf/1904.08366)

