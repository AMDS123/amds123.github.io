---
layout: post
title: "An observable time series based SLAM algorithm for deforming environment"
date: 2019-06-20 11:24:15
categories: arXiv_RO
tags: arXiv_RO Face SLAM
author: Jingwei Song, Liang Zhao, Shoudong Huang, Gamini Dissanayake
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the back-end of simultaneous localization and mapping (SLAM) problem in deforming environment, where robot localizes itself and tracks multiple non-rigid soft surface using its onboard sensor measurements. An elaborate analysis is conducted on conventional deformation modelling method, Embedded Deformation (ED) graph. We demonstrate and prove that the ED graph widely used in such scenarios is unobservable and leads to multiple solutions unless suitable priors are provided. Example as well as theoretical prove are provided to show the ambiguity of ED graph and camera pose. In modelling non-rigid scenario with ED graph, motion priors of the deforming environment is essential to separate robot pose and deforming environment. The conclusion can be extrapolated to any free form deformation formulation. In solving the observability, this research proposes a preliminary deformable SLAM approach to estimate robot pose in complex environments that exhibits regular motion. A strategy that approximates deformed shape using a linear combination of several previous shapes is proposed to avoid the ambiguity in robot movement and rigid and non-rigid motions of the environment. Fisher information matrix rank analysis with a base case is discussed to prove the effectiveness. Moreover, the proposed algorithm is validated extensively on Monte Carlo simulations and real experiments. It is demonstrated that the new algorithm significantly outperforms conventional rigid SLAM and ED based SLAM especially in scenarios where there is large deformation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08563](http://arxiv.org/abs/1906.08563)

##### PDF
[http://arxiv.org/pdf/1906.08563](http://arxiv.org/pdf/1906.08563)

