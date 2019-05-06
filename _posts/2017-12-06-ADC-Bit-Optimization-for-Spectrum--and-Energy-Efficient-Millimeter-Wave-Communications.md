---
layout: post
title: "ADC Bit Optimization for Spectrum- and Energy-Efficient Millimeter Wave Communications"
date: 2017-12-06 03:16:34
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jinseok Choi, Junmo Sung, Brian L. Evans, Alan Gatherer
mathjax: true
---

* content
{:toc}

##### Abstract
A spectrum- and energy-efficient system is essential for millimeter wave communication systems that require large antenna arrays with power-demanding ADCs. We propose an ADC bit allocation (BA) algorithm that solves a minimum mean squared quantization error problem under a power constraint. Unlike existing BA methods that only consider an ADC power constraint, the proposed algorithm regards total receiver power constraint for a hybrid analog-digital beamforming architecture. The major challenge is the non-linearities in the minimization problem. To address this issue, we first convert the problem into a convex optimization problem through real number relaxation and substitution of ADC resolution switching power with constant average switching power. Then, we derive a closed-form solution by fixing the number of activated radio frequency (RF) chains M. Leveraging the solution, the binary search finds the optimal M and its corresponding optimal solution. We also provide an off-line training and modeling approach to estimate the average switching power. Simulation results validate the spectral and energy efficiency of the proposed algorithm. In particular, existing state-of-the-art digital beamformers can be used in the system in conjunction with the BA algorithm as it makes the quantization error negligible in the low-resolution regime.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.02018](https://arxiv.org/abs/1712.02018)

##### PDF
[https://arxiv.org/pdf/1712.02018](https://arxiv.org/pdf/1712.02018)

