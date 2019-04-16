---
layout: post
title: "Graph Memory Networks for Molecular Activity Prediction"
date: 2018-01-27 04:57:00
categories: arXiv_CV
tags: arXiv_CV Prediction Memory_Networks
author: Trang Pham, Truyen Tran, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
Molecular activity prediction is critical in drug design. Machine learning techniques such as kernel methods and random forests have been successful for this task. These models require fixed-size feature vectors as input while the molecules are variable in size and structure. As a result, fixed-size fingerprint representation is poor in handling substructures for large molecules. In addition, molecular activity tests, or a so-called BioAssays, are relatively small in the number of tested molecules due to its complexity. Here we approach the problem through deep neural networks as they are flexible in modeling structured data such as grids, sequences and graphs. We train multiple BioAssays using a multi-task learning framework, which combines information from multiple sources to improve the performance of prediction, especially on small datasets. We propose Graph Memory Network (GraphMem), a memory-augmented neural network to model the graph structure in molecules. GraphMem consists of a recurrent controller coupled with an external memory whose cells dynamically interact and change through a multi-hop reasoning process. Applied to the molecules, the dynamic interactions enable an iterative refinement of the representation of molecular graphs with multiple bond types. GraphMem is capable of jointly training on multiple datasets by using a specific-task query fed to the controller as an input. We demonstrate the effectiveness of the proposed model for separately and jointly training on more than 100K measurements, spanning across 9 BioAssay activity tests.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.02622](https://arxiv.org/abs/1801.02622)

##### PDF
[https://arxiv.org/pdf/1801.02622](https://arxiv.org/pdf/1801.02622)

