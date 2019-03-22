---
layout: post
title: "Short-Term Prediction and Multi-Camera Fusion on Semantic Grids"
date: 2019-03-21 12:49:31
categories: arXiv_AI
tags: arXiv_AI Knowledge Segmentation Face Semantic_Segmentation Prediction
author: Lukas Hoyer, Patrick Kesper, Volker Fischer
mathjax: true
---

* content
{:toc}

##### Abstract
An environment representation (ER) is a substantial part of every autonomous system. It introduces a common interface between perception and other system components, such as decision making, and allows downstream algorithms to deal with abstracted data without knowledge of the used sensor. In this work, we propose and evaluate a novel architecture that generates an egocentric, grid-based, predictive, and semantically-interpretable ER. In particular, we provide a proof of concept for the spatio-temporal fusion of multiple camera sequences and short-term prediction in such an ER. Our design utilizes a strong semantic segmentation network together with depth and egomotion estimates to first extract semantic information from multiple camera streams and then transform these separately into egocentric temporally-aligned bird's-eye view grids. A deep encoder-decoder network is trained to fuse a stack of these grids into a unified semantic grid representation and to predict the dynamics of its surrounding. We evaluate this representation on real-world sequences of the Cityscapes dataset and show that our architecture can make accurate predictions in complex sensor fusion scenarios and significantly outperforms a model-driven baseline in a category-based evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08960](http://arxiv.org/abs/1903.08960)

##### PDF
[http://arxiv.org/pdf/1903.08960](http://arxiv.org/pdf/1903.08960)

