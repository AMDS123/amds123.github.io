---
layout: post
title: "Cascaded Context Pyramid for Full-Resolution 3D Semantic Scene Completion"
date: 2019-08-01 13:27:41
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning Prediction
author: Pingping Zhang, Wei Liu, Yinjie Lei, Huchuan Lu, Xiaoyun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic Scene Completion (SSC) aims to simultaneously predict the volumetric occupancy and semantic category of a 3D scene. It helps intelligent devices to understand and interact with the surrounding scenes. Due to the high-memory requirement, current methods only produce low-resolution completion predictions, and generally lose the object details. Furthermore, they also ignore the multi-scale spatial contexts, which play a vital role for the 3D inference. To address these issues, in this work we propose a novel deep learning framework, named Cascaded Context Pyramid Network (CCPNet), to jointly infer the occupancy and semantic labels of a volumetric 3D scene from a single depth image. The proposed CCPNet improves the labeling coherence with a cascaded context pyramid. Meanwhile, based on the low-level features, it progressively restores the fine-structures of objects with Guided Residual Refinement (GRR) modules. Our proposed framework has three outstanding advantages: (1) it explicitly models the 3D spatial context for performance improvement; (2) full-resolution 3D volumes are produced with structure-preserving details; (3) light-weight models with low-memory requirements are captured with a good extensibility. Extensive experiments demonstrate that in spite of taking a single-view depth map, our proposed framework can generate high-quality SSC results, and outperforms state-of-the-art approaches on both the synthetic SUNCG and real NYU datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00382](http://arxiv.org/abs/1908.00382)

##### PDF
[http://arxiv.org/pdf/1908.00382](http://arxiv.org/pdf/1908.00382)

