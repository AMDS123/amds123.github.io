---
layout: post
title: "End-to-end Learning for Graph Decomposition"
date: 2018-12-23 16:21:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Jie Song, Bjoern Andres, Michael Black, Otmar Hilliges, Siyu Tang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel end-to-end trainable framework for the graph decomposition problem. The minimum cost multicut problem is first converted to an unconstrained binary cubic formulation where cycle consistency constraints are incorporated into the objective function. The new optimization problem can be viewed as a Conditional Random Field (CRF) in which the random variables are associated with the binary edge labels of the initial graph and the hard constraints are introduced in the CRF as high-order potentials. The parameters of a standard Neural Network and the fully differentiable CRF are optimized in an end-to-end manner. Furthermore, our method utilizes the cycle constraints as meta-supervisory signals during the learning of the deep feature representations by taking the dependencies between the output random variables into account. We present analyses of the end-to-end learned representations, showing the impact of the joint training, on the task of clustering images of MNIST. We also validate the effectiveness of our approach both for the feature learning and the final clustering on the challenging task of real-world multi-person pose estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09737](http://arxiv.org/abs/1812.09737)

##### PDF
[http://arxiv.org/pdf/1812.09737](http://arxiv.org/pdf/1812.09737)

