---
layout: post
title: "Face Alignment using a 3D Deeply-initialized Ensemble of Regression Trees"
date: 2019-02-05 18:07:17
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Roberto Valle (1), Jos&#xe9; M. Buenaposada (2), Antonio Vald&#xe9;s (3), Luis Baumela (1) ((1) Universidad Polit&#xe9;cnica de Madrid, (2) Universidad Rey Juan Carlos, (3) Universidad Complutense de Madrid)
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment algorithms locate a set of landmark points in images of faces taken in unrestricted situations. State-of-the-art approaches typically fail or lose accuracy in the presence of occlusions, strong deformations, large pose variations and ambiguous configurations. In this paper we present 3DDE, a robust and efficient face alignment algorithm based on a coarse-to-fine cascade of ensembles of regression trees. It is initialized by robustly fitting a 3D face model to the probability maps produced by a convolutional neural network. With this initialization we address self-occlusions and large face rotations. Further, the regressor implicitly imposes a prior face shape on the solution, addressing occlusions and ambiguous face configurations. Its coarse-to-fine structure tackles the combinatorial explosion of parts deformation. In the experiments performed, 3DDE improves the state-of-the-art in 300W, COFW, AFLW and WFLW data sets. Finally, given that 3DDE can also be trained with missing and occluded landmarks, we have been able to perform cross-dataset experiments that reveal the existence of a significant data set bias in these benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01831](http://arxiv.org/abs/1902.01831)

##### PDF
[http://arxiv.org/pdf/1902.01831](http://arxiv.org/pdf/1902.01831)

