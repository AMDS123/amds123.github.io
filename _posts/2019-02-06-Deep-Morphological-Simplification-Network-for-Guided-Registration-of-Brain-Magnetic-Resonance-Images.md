---
layout: post
title: "Deep Morphological Simplification Network for Guided Registration of Brain Magnetic Resonance Images"
date: 2019-02-06 18:58:58
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Deep_Learning
author: Dongming Wei, Zhengwang Wu, Gang Li, Xiaohuan Cao, Dinggang Shen, Qian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Deformable brain MR image registration is challenging due to large inter-subject anatomical variation. For example, the highly complex cortical folding pattern makes it hard to accurately align corresponding cortical structures of individual images. In this paper, we propose a novel deep learning way to simplify the difficult registration problem of brain MR images. Methods: We train a morphological simplification network (MS-Net), which can generate a "simple" image with less anatomical details based on the "complex" input. With MS-Net, the complexity of the fixed image or the moving image under registration can be reduced gradually, thus building an individual (simplification) trajectory represented by MS-Net outputs. Since the generated images at the ends of the two trajectories (of the fixed and moving images) are so simple and very similar in appearance, they are easy to register. Thus, the two trajectories can act as a bridge to link the fixed and the moving images, and guide their registration. Results: Our experiments show that the proposed method can achieve highly accurate registration performance on different datasets (i.e., NIREP, LPBA, IBSR, CUMC, and MGH). Moreover, the method can be also easily transferred across diverse image datasets and obtain superior accuracy on surface alignment. Conclusion and Significance: We propose MS-Net as a powerful and flexible tool to simplify brain MR images and their registration. To our knowledge, this is the first work to simplify brain MR image registration by deep learning, instead of estimating deformation field directly.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02342](http://arxiv.org/abs/1902.02342)

##### PDF
[http://arxiv.org/pdf/1902.02342](http://arxiv.org/pdf/1902.02342)

