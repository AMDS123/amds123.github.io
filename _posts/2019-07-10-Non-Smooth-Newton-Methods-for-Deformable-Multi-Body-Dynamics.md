---
layout: post
title: "Non-Smooth Newton Methods for Deformable Multi-Body Dynamics"
date: 2019-07-10 09:27:44
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Miles Macklin, Kenny Erleben, Matthias M&#xfc;ller, Nuttapong Chentanez, Stefan Jeschke, Viktor Makoviychuk
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for the simulation of rigid and deformable bodies in the presence of contact and friction. Our method is based on a non-smooth Newton iteration that solves the underlying nonlinear complementarity problems (NCPs) directly. This approach allows us to support nonlinear dynamics models, including hyperelastic deformable bodies and articulated rigid mechanisms, coupled through a smooth isotropic friction model. The fixed-point nature of our method means it requires only the solution of a symmetric linear system as a building block. We propose a new complementarity preconditioner for NCP functions that improves convergence, and we develop an efficient GPU-based solver based on the conjugate residual (CR) method that is suitable for interactive simulations. We show how to improve robustness using a new geometric stiffness approximation and evaluate our method's performance on a number of robotics simulation scenarios, including dexterous manipulation and training using reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04587](http://arxiv.org/abs/1907.04587)

##### PDF
[http://arxiv.org/pdf/1907.04587](http://arxiv.org/pdf/1907.04587)

