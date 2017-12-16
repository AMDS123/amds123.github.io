---
layout: post
title: "Target Oriented High Resolution SAR Image Formation via Semantic Information Guided Regularizations"
date: 2017-04-24 08:27:06
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge
author: Biao Hou, Zaidao Wen, Licheng Jiao, Qian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Sparsity-regularized synthetic aperture radar (SAR) imaging framework has shown its remarkable performance to generate a feature enhanced high resolution image, in which a sparsity-inducing regularizer is involved by exploiting the sparsity priors of some visual features in the underlying image. However, since the simple prior of low level features are insufficient to describe different semantic contents in the image, this type of regularizer will be incapable of distinguishing between the target of interest and unconcerned background clutters. As a consequence, the features belonging to the target and clutters are simultaneously affected in the generated image without concerning their underlying semantic labels. To address this problem, we propose a novel semantic information guided framework for target oriented SAR image formation, which aims at enhancing the interested target scatters while suppressing the background clutters. Firstly, we develop a new semantics-specific regularizer for image formation by exploiting the statistical properties of different semantic categories in a target scene SAR image. In order to infer the semantic label for each pixel in an unsupervised way, we moreover induce a novel high-level prior-driven regularizer and some semantic causal rules from the prior knowledge. Finally, our regularized framework for image formation is further derived as a simple iteratively reweighted $\ell_1$ minimization problem which can be conveniently solved by many off-the-shelf solvers. Experimental results demonstrate the effectiveness and superiority of our framework for SAR image formation in terms of target enhancement and clutters suppression, compared with the state of the arts. Additionally, the proposed framework opens a new direction of devoting some machine learning strategies to image formation, which can benefit the subsequent decision making tasks.

##### Abstract (translated by Google)
稀疏正则化合成孔径雷达（SAR）成像框架已经显示出其显着的性能，以生成特征增强的高分辨率图像，其中通过利用基础图像中一些视觉特征的稀疏性先验来引入稀疏诱导正则化器。然而，由于低级特征的简单先验不足以描述图像中的不同语义内容，这种类型的正规化器将不能区分兴趣目标和无关背景杂波。结果，属于目标和杂波的特征在生成的图像中同时受到影响，而不涉及其基本语义标签。为了解决这个问题，我们提出了一种面向目标的SAR图像形成的新的语义信息引导框架，旨在提高目标散射的同时抑制背景杂波。首先，利用目标场景SAR图像中不同语义类别的统计特性，开发了一种新的语义特异化图像形成规则。为了以无监督的方式推导出每个像素的语义标签，我们还引入了一个新的高层次的先验正则化规则和一些先验知识的语义因果规则。最后，我们正规化的图像形成框架进一步推导为一个简单的迭代重新加权$ \ ell_1 $最小化问题，可以通过许多现成的求解器方便地解决。实验结果表明，相比于现有技术，我们的SAR图像形成框架在目标增强和杂波抑制方面的有效性和优越性。另外，所提出的框架开辟了将图像形成的一些机器学习策略的一个新的方向，这将有利于后续的决策任务。

##### URL
[https://arxiv.org/abs/1704.07082](https://arxiv.org/abs/1704.07082)

##### PDF
[https://arxiv.org/pdf/1704.07082](https://arxiv.org/pdf/1704.07082)

