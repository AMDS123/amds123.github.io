---
layout: post
title: "Direct Neural Network 3D Image Reconstruction of Radon Encoded Data"
date: 2019-08-19 19:03:13
categories: arXiv_CV
tags: arXiv_CV
author: William Whiteley, Jens Gregor
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network image reconstruction directly from measurement data is a growing field of research, but until now has been limited to producing small (e.g. 128x128) 2D images by the large memory requirements of the previously suggested networks. In order to facilitate further research with direct reconstruction, we developed a more efficient network capable of 3D reconstruction of Radon encoded data with a relatively large image matrix (e.g. 400x400). Our proposed network is able to produce image quality comparable to the benchmark Ordered Subsets Expectation Maximization (OSEM) algorithm. We address the most memory intensive aspect of transforming the data from sinogram space to image space through a specially designed Radon inversion layer. We insert this layer between an initial network segment designed to encode the sinogram input and an output segment designed to refine and scale the initial image estimate to produce the final image. We demonstrate 3D reconstructions comparable to OSEM for 1, 4, 8 and 16 slices with no modifications to the network's architecture, capacity or hyper-parameters on a data set of simulated PET whole-body scans. When batch operations are considered, this network can reconstruct an entire PET whole-body volume in a single pass or about one second. Although results in this paper are on PET data, the proposed methods would be equally applicable to X-ray CT or any other Radon encoded measurement data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07516](http://arxiv.org/abs/1908.07516)

##### PDF
[http://arxiv.org/pdf/1908.07516](http://arxiv.org/pdf/1908.07516)

