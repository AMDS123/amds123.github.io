---
layout: post
title: "Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation"
date: 2019-01-10 01:05:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Classification Prediction
author: Chenxi Liu, Liang-Chieh Chen, Florian Schroff, Hartwig Adam, Wei Hua, Alan Yuille, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Neural Architecture Search (NAS) has successfully identified neural network architectures that exceed human designed ones on large-scale image classification problems. In this paper, we study NAS for semantic image segmentation, an important computer vision task that assigns a semantic label to every pixel in an image. Existing works often focus on searching the repeatable cell structure, while hand-designing the outer network structure that controls the spatial resolution changes. This choice simplifies the search space, but becomes increasingly problematic for dense image prediction which exhibits a lot more network level architectural variations. Therefore, we propose to search the network level structure in addition to the cell level structure, which forms a hierarchical architecture search space. We present a network level search space that includes many popular designs, and develop a formulation that allows efficient gradient-based architecture search (3 P100 GPU days on Cityscapes images). We demonstrate the effectiveness of the proposed method on the challenging Cityscapes, PASCAL VOC 2012, and ADE20K datasets. Without any ImageNet pretraining, our architecture searched specifically for semantic image segmentation attains state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.02985](https://arxiv.org/abs/1901.02985)

##### PDF
[https://arxiv.org/pdf/1901.02985](https://arxiv.org/pdf/1901.02985)

