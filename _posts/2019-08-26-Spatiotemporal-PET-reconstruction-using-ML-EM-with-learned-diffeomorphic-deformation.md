---
layout: post
title: "Spatiotemporal PET reconstruction using ML-EM with learned diffeomorphic deformation"
date: 2019-08-26 08:04:49
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Ozan &#xd6;ktem, Camille Pouchol, Olivier Verdier
mathjax: true
---

* content
{:toc}

##### Abstract
Patient movement in emission tomography deteriorates reconstruction quality because of motion blur. Gating the data improves the situation somewhat: each gate contains a movement phase which is approximately stationary. A standard method is to use only the data from a few gates, with little movement between them. However, the corresponding loss of data entails an increase of noise. Motion correction algorithms have been implemented to take into account all the gated data, but they do not scale well, especially not in 3D. We propose a novel motion correction algorithm which addresses the scalability issue. Our approach is to combine an enhanced ML-EM algorithm with deep learning based movement registration. The training is unsupervised, and with artificial data. We expect this approach to scale very well to higher resolutions and to 3D, as the overall cost of our algorithm is only marginally greater than that of a standard ML-EM algorithm. We show that we can significantly decrease the noise corresponding to a limited number of gates.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09515](http://arxiv.org/abs/1908.09515)

##### PDF
[http://arxiv.org/pdf/1908.09515](http://arxiv.org/pdf/1908.09515)

