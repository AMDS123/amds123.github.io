---
layout: post
title: "CGC-Net: Cell Graph Convolutional Network for Grading of Colorectal Cancer Histology Images"
date: 2019-09-03 11:25:00
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yanning Zhou, Simon Graham, Navid Alemi Koohbanani, Muhammad Shaban, Pheng-Ann Heng, Nasir Rajpoot
mathjax: true
---

* content
{:toc}

##### Abstract
Colorectal cancer (CRC) grading is typically carried out by assessing the degree of gland formation within histology images. To do this, it is important to consider the overall tissue micro-environment by assessing the cell-level information along with the morphology of the gland. However, current automated methods for CRC grading typically utilise small image patches and therefore fail to incorporate the entire tissue micro-architecture for grading purposes. To overcome the challenges of CRC grading, we present a novel cell-graph convolutional neural network (CGC-Net) that converts each large histology image into a graph, where each node is represented by a nucleus within the original image and cellular interactions are denoted as edges between these nodes according to node similarity. The CGC-Net utilises nuclear appearance features in addition to the spatial location of nodes to further boost the performance of the algorithm. To enable nodes to fuse multi-scale information, we introduce Adaptive GraphSage, which is a graph convolution technique that combines multi-level features in a data-driven way. Furthermore, to deal with redundancy in the graph, we propose a sampling technique that removes nodes in areas of dense nuclear activity. We show that modeling the image as a graph enables us to effectively consider a much larger image (around 16$\times$ larger) than traditional patch-based approaches and model the complex structure of the tissue micro-environment. We construct cell graphs with an average of over 3,000 nodes on a large CRC histology image dataset and report state-of-the-art results as compared to recent patch-based as well as contextual patch-based techniques, demonstrating the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01068](https://arxiv.org/abs/1909.01068)

##### PDF
[https://arxiv.org/pdf/1909.01068](https://arxiv.org/pdf/1909.01068)

