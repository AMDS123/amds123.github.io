---
layout: post
title: "3D Instance Segmentation via Multi-task Metric Learning"
date: 2019-06-20 14:14:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Jean Lahoud, Bernard Ghanem, Marc Pollefeys, Martin R. Oswald
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for instance label segmentation of dense 3D voxel grids. We target volumetric scene representations which have been acquired with depth sensors or multi-view stereo methods and which have been processed with semantic 3D reconstruction or scene completion methods. The main task is to learn shape information about individual object instances in order to accurately separate them, including connected and incompletely scanned objects. We solve the 3D instance-labeling problem with a multi-task learning strategy. The first goal is to learn an abstract feature embedding which groups voxels with the same instance label close to each other while separating clusters with different instance labels from each other. The second goal is to learn instance information by estimating directional information of the instances' centers of mass densely for each voxel. This is particularly useful to find instance boundaries in the clustering post-processing step, as well as for scoring the quality of segmentations for the first goal. Both synthetic and real-world experiments demonstrate the viability of our approach. Our method achieves state-of-the-art performance on the ScanNet 3D instance segmentation benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08650](http://arxiv.org/abs/1906.08650)

##### PDF
[http://arxiv.org/pdf/1906.08650](http://arxiv.org/pdf/1906.08650)

