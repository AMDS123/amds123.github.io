---
layout: post
title: "Fast, Accurate and Fully Parallelizable Digital Image Correlation"
date: 2017-10-12 05:36:32
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Optimization Relation
author: Peihan Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Digital image correlation (DIC) is a widely used optical metrology for surface deformation measurements. DIC relies on nonlinear optimization method. Thus an initial guess is quite important due to its influence on the converge characteristics of the algorithm. In order to obtain a reliable, accurate initial guess, a reliability-guided digital image correlation (RG-DIC) method, which is able to intelligently obtain a reliable initial guess without using time-consuming integer-pixel registration, was proposed. However, the RG-DIC and its improved methods are path-dependent and cannot be fully parallelized. Besides, it is highly possible that RG-DIC fails in the full-field analysis of deformation without manual intervention if the deformation fields contain large areas of discontinuous deformation. Feature-based initial guess is highly robust while it is relatively time-consuming. Recently, path-independent algorithm, fast Fourier transform-based cross correlation (FFT-CC) algorithm, was proposed to estimate the initial guess. Complete parallelizability is the major advantage of the FFT-CC algorithm, while it is sensitive to small deformation. Wu et al proposed an efficient integer-pixel search scheme, but the parameters of this algorithm are set by the users empirically. In this technical note, a fully parallelizable DIC method is proposed. Different from RG-DIC method, the proposed method divides DIC algorithm into two parts: full-field initial guess estimation and sub-pixel registration. The proposed method has the following benefits: 1) providing a pre-knowledge of deformation fields; 2) saving computational time; 3) reducing error propagation; 4) integratability with well-established DIC algorithms; 5) fully parallelizability.

##### Abstract (translated by Google)
数字图像相关（DIC）是表面变形测量中广泛使用的光学计量学。 DIC依靠非线性优化方法。因此，由于其对算法的收敛特性的影响，初始猜测是相当重要的。为了获得可靠，准确的初始猜测，提出了一种可靠性指导的数字图像相关（RG-DIC）方法，该方法能够在不使用费时的整像素配准的情况下智能地获得可靠的初始猜测。但是，RG-DIC及其改进的方法是路径依赖的，不能完全并行化。此外，如果变形场包含大面积的不连续变形，则RG-DIC很有可能在没有人工干预的情况下进行全场变形分析。基于特征的初始猜测非常强大，但相对耗时。最近，提出了路径无关算法，基于快速傅立叶变换的互相关（FFT-CC）算法来估计初始猜测。完整的并行性是FFT-CC算法的主要优点，对小变形敏感。 Wu等人提出了一种高效的整像素搜索方案，但该算法的参数是由用户根据经验设定的。在这个技术说明中，提出了完全可并行化的DIC方法。与RG-DIC方法不同，所提出的方法将DIC算法分为两部分：全场初始猜测估计和子像素配准。该方法具有以下优点：1）提供变形场的预知识; 2）节省计算时间; 3）减少错误传播; 4）与完善的DIC算法的可集成性; 5）完全可并行性。

##### URL
[https://arxiv.org/abs/1710.04374](https://arxiv.org/abs/1710.04374)

##### PDF
[https://arxiv.org/pdf/1710.04374](https://arxiv.org/pdf/1710.04374)

