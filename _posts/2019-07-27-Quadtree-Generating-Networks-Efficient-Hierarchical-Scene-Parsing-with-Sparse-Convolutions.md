---
layout: post
title: "Quadtree Generating Networks: Efficient Hierarchical Scene Parsing with Sparse Convolutions"
date: 2019-07-27 00:20:12
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Semantic_Segmentation Inference Prediction
author: Kashyap Chitta, Jose M. Alvarez, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation with Convolutional Neural Networks is a memory-intensive task due to the high spatial resolution of feature maps and output predictions. In this paper, we present Quadtree Generating Networks (QGNs), a novel approach able to drastically reduce the memory footprint of modern semantic segmentation networks. The key idea is to use quadtrees to represent the predictions and target segmentation masks instead of dense pixel grids. Our quadtree representation enables hierarchical processing of an input image, with the most computationally demanding layers only being used at regions in the image containing boundaries between classes. In addition, given a trained model, our representation enables flexible inference schemes to trade-off accuracy and computational cost, allowing the network to adapt in constrained situations such as embedded devices. We demonstrate the benefits of our approach on the Cityscapes, SUN-RGBD and ADE20k datasets. On Cityscapes, we obtain an relative 3% mIoU improvement compared to a dilated network with similar memory consumption; and only receive a 3% relative mIoU drop compared to a large dilated network, while reducing memory consumption by over 4$\times$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11821](http://arxiv.org/abs/1907.11821)

##### PDF
[http://arxiv.org/pdf/1907.11821](http://arxiv.org/pdf/1907.11821)

