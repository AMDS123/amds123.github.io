---
layout: post
title: "Learning Deep CNN Denoiser Prior for Image Restoration"
date: 2017-04-11 12:30:46
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Kai Zhang, Wangmeng Zuo, Shuhang Gu, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based optimization methods and discriminative learning methods have been the two dominant strategies for solving various inverse problems in low-level vision. Typically, those two kinds of methods have their respective merits and drawbacks, e.g., model-based optimization methods are flexible for handling different inverse problems but are usually time-consuming with sophisticated priors for the purpose of good performance; in the meanwhile, discriminative learning methods have fast testing speed but their application range is greatly restricted by the specialized task. Recent works have revealed that, with the aid of variable splitting techniques, denoiser prior can be plugged in as a modular part of model-based optimization methods to solve other inverse problems (e.g., deblurring). Such an integration induces considerable advantage when the denoiser is obtained via discriminative learning. However, the study of integration with fast discriminative denoiser prior is still lacking. To this end, this paper aims to train a set of fast and effective CNN (convolutional neural network) denoisers and integrate them into model-based optimization method to solve other inverse problems. Experimental results demonstrate that the learned set of denoisers not only achieve promising Gaussian denoising results but also can be used as prior to deliver good performance for various low-level vision applications.

##### Abstract (translated by Google)
基于模型的优化方法和判别式学习方法一直是解决低级视觉中各种反问题的两个主要策略。通常，这两种方法各有优缺点，例如，基于模型的优化方法对于处理不同的逆问题是灵活的，但是为了良好的性能，通常是耗时的，并且具有复杂的先验;同时，判别式学习方法检测速度快，但其应用范围受到专门任务的极大限制。最近的研究表明，借助可变分裂技术，可以将去噪声优先插入作为基于模型的优化方法的模块化部分来解决其他反问题（例如去模糊）。当通过判别式学习获得降噪器时，这种整合引起了相当大的优势。然而，与快速鉴别降噪器之前的整合研究仍然缺乏。为此，本文旨在训练一组快速有效的CNN（卷积神经网络）分解器，并将其集成到基于模型的优化方法中，以解决其他逆问题。实验结果表明，所学习的分解器集合不仅可以实现有希望的高斯去噪效果，而且可以作为以前的实现，为各种低阶视觉应用提供良好的性能。

##### URL
[https://arxiv.org/abs/1704.03264](https://arxiv.org/abs/1704.03264)

##### PDF
[https://arxiv.org/pdf/1704.03264](https://arxiv.org/pdf/1704.03264)

