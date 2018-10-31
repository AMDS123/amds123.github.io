---
layout: post
title: "VR-SGD: A Simple Stochastic Variance Reduction Method for Machine Learning"
date: 2018-10-28 15:03:47
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Fanhua Shang, Kaiwen Zhou, Hongying Liu, James Cheng, Ivor W. Tsang, Lijun Zhang, Dacheng Tao, Licheng Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple variant of the original SVRG, called variance reduced stochastic gradient descent (VR-SGD). Unlike the choices of snapshot and starting points in SVRG and its proximal variant, Prox-SVRG, the two vectors of VR-SGD are set to the average and last iterate of the previous epoch, respectively. The settings allow us to use much larger learning rates, and also make our convergence analysis more challenging. We also design two different update rules for smooth and non-smooth objective functions, respectively, which means that VR-SGD can tackle non-smooth and/or non-strongly convex problems directly without any reduction techniques. Moreover, we analyze the convergence properties of VR-SGD for strongly convex problems, which show that VR-SGD attains linear convergence. Different from its counterparts that have no convergence guarantees for non-strongly convex problems, we also provide the convergence guarantees of VR-SGD for this case, and empirically verify that VR-SGD with varying learning rates achieves similar performance to its momentum accelerated variant that has the optimal convergence rate $\mathcal{O}(1/T^2)$. Finally, we apply VR-SGD to solve various machine learning problems, such as convex and non-convex empirical risk minimization, and leading eigenvalue computation. Experimental results show that VR-SGD converges significantly faster than SVRG and Prox-SVRG, and usually outperforms state-of-the-art accelerated methods, e.g., Katyusha.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.09932](http://arxiv.org/abs/1802.09932)

##### PDF
[http://arxiv.org/pdf/1802.09932](http://arxiv.org/pdf/1802.09932)

