---
layout: post
title: "Region-specific Diffeomorphic Metric Mapping"
date: 2019-06-01 03:14:15
categories: arXiv_CV
tags: arXiv_CV Regularization Deep_Learning
author: Zhengyang Shen, Fran&#xe7;ois-Xavier Vialard, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a region-specific diffeomorphic metric mapping (RDMM) registration approach. RDMM is non-parametric, estimating spatio-temporal velocity fields which parameterize the sought-for spatial transformation. Regularization of these velocity fields is necessary. However, while existing non-parametric registration approaches, e.g., the large displacement diffeomorphic metric mapping (LDDMM) model, use a fixed spatially-invariant regularization our model advects a spatially-varying regularizer with the estimated velocity field, thereby naturally attaching a spatio-temporal regularizer to deforming objects. We explore a family of RDMM registration approaches: 1) a registration model where regions with separate regularizations are pre-defined (e.g., in an atlas space), 2) a registration model where a general spatially-varying regularizer is estimated, and 3) a registration model where the spatially-varying regularizer is obtained via an end-to-end trained deep learning (DL) model. We provide a variational derivation of RDMM, show that the model can assure diffeomorphic transformations in the continuum, and that LDDMM is a particular instance of RDMM. To evaluate RDMM performance we experiment 1) on synthetic 2D data and 2) on two 3D datasets: knee magnetic resonance images (MRIs) of the Osteoarthritis Initiative (OAI) and computed tomography images (CT) of the lung. Results show that our framework achieves state-of-the-art image registration performance, while providing additional information via a learned spatio-temoporal regularizer. Further, our deep learning approach allows for very fast RDMM and LDDMM estimations. Our code will be open-sourced. Code is available at https://github.com/uncbiag/registration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00139](http://arxiv.org/abs/1906.00139)

##### PDF
[http://arxiv.org/pdf/1906.00139](http://arxiv.org/pdf/1906.00139)

