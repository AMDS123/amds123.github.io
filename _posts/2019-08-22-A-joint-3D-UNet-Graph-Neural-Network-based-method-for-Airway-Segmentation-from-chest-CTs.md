---
layout: post
title: "A joint 3D UNet-Graph Neural Network-based method for Airway Segmentation from chest CTs"
date: 2019-08-22 20:32:01
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Antonio Garcia-Uceda Juarez, Raghavendra Selvan, Zaigham Saghir, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end deep learning segmentation method by combining a 3D UNet architecture with a graph neural network (GNN) model. In this approach, the convolutional layers at the deepest level of the UNet are replaced by a GNN-based module with a series of graph convolutions. The dense feature maps at this level are transformed into a graph input to the GNN module. The incorporation of graph convolutions in the UNet provides nodes in the graph with information that is based on node connectivity, in addition to the local features learnt through the downsampled paths. This information can help improve segmentation decisions. By stacking several graph convolution layers, the nodes can access higher order neighbourhood information without substantial increase in computational expense. We propose two types of node connectivity in the graph adjacency: i) one predefined and based on a regular node neighbourhood, and ii) one dynamically computed during training and using the nearest neighbour nodes in the feature space. We have applied this method to the task of segmenting the airway tree from chest CT scans. Experiments have been performed on 32 CTs from the Danish Lung Cancer Screening Trial dataset. We evaluate the performance of the UNet-GNN models with two types of graph adjacency and compare it with the baseline UNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08588](http://arxiv.org/abs/1908.08588)

##### PDF
[http://arxiv.org/pdf/1908.08588](http://arxiv.org/pdf/1908.08588)

