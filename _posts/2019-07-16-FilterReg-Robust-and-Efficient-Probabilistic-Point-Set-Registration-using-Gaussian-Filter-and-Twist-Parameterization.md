---
layout: post
title: "FilterReg: Robust and Efficient Probabilistic Point-Set Registration using Gaussian Filter and Twist Parameterization"
date: 2019-07-16 17:34:47
categories: arXiv_CV
tags: arXiv_CV Attention
author: Wei Gao, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic point-set registration methods have been gaining more attention for their robustness to noise, outliers and occlusions. However, these methods tend to be much slower than the popular iterative closest point (ICP) algorithms, which severely limits their usability. In this paper, we contribute a novel probabilistic registration method that achieves state-of-the-art robustness as well as substantially faster computational performance than modern ICP implementations. This is achieved using a rigorous yet computationally-efficient probabilistic formulation. Point-set registration is cast as a maximum likelihood estimation and solved using the EM algorithm. We show that with a simple augmentation, the E step can be formulated as a filtering problem, allowing us to leverage advances in efficient Gaussian filtering methods. We also propose a customized permutohedral filter for improved efficiency while retaining sufficient accuracy for our task. Additionally, we present a simple and efficient twist parameterization that generalizes our method to the registration of articulated and deformable objects. For articulated objects, the complexity of our method is almost independent of the Degrees Of Freedom (DOFs), which makes it highly efficient even for high DOF systems. The results demonstrate the proposed method consistently outperforms many competitive baselines on a variety of registration tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10136](http://arxiv.org/abs/1811.10136)

##### PDF
[http://arxiv.org/pdf/1811.10136](http://arxiv.org/pdf/1811.10136)

