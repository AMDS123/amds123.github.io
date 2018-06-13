---
layout: post
title: "Learning Deep Similarity Metric for 3D MR-TRUS Registration"
date: 2018-06-12 14:13:00
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Grant Haskins, Jochen Kruecker, Uwe Kruger, Sheng Xu, Peter A. Pinto, Brad J. Wood, Pingkun Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: The fusion of transrectal ultrasound (TRUS) and magnetic resonance (MR) images for guiding targeted prostate biopsy has significantly improved the biopsy yield of aggressive cancers. A key component of MR-TRUS fusion is image registration. However, it is very challenging to obtain a robust automatic MR-TRUS registration due to the large appearance difference between the two imaging modalities. The work presented in this paper aims to tackle this problem by addressing two challenges: (i) the definition of a suitable similarity metric and (ii) the determination of a suitable optimization strategy. 
 Methods: This work proposes the use of a deep convolutional neural network to learn a suitable similarity metric. We also use a composite optimization strategy to explore the solution space for optimizing the learned metric for image registration. 
 Results: The learned similarity metric outperforms mutual information and the results indicate that the overall registration framework has a large capture range. The proposed deep similarity metric based approach obtained the mean TRE of 4.24mm (with an initial TRE of 16mm) for this challenging problem. 
 Conclusion: Learned metric based on deep learning can be used to assess the quality of any given image registration and can be used in conjunction with the aforementioned optimization framework to perform automatic registration that is robust to poor initialization.

##### Abstract (translated by Google)
目的：经直肠超声（TRUS）和磁共振（MR）图像融合以指导靶向前列腺活检显着提高了侵袭性癌症活检的产量。 MR-TRUS融合的关键部分是图像配准。然而，由于两种成像模式之间的大的外观差异，获得鲁棒的自动MR-TRUS配准是非常具有挑战性的。本文提出的工作旨在通过解决两个挑战来解决这个问题：（i）定义合适的相似性度量和（ii）确定合适的优化策略。
 方法：本工作提出使用深度卷积神经网络来学习合适的相似性度量。我们还使用复合优化策略来探索优化图像配准的学习度量的解决方案空间。
 结果：学习相似性度量优于互信息，结果表明整体登记框架具有较大的捕获范围。所提出的基于深度相似性度量的方法针对这一具有挑战性的问题获得了4.24mm的平均TRE（初始TRE为16mm）。
 结论：基于深度学习的学习度量可用于评估任何给定图像配准的质量，并可与上述优化框架结合使用，以执行对不良初始化有效的自动配准。

##### URL
[http://arxiv.org/abs/1806.04548](http://arxiv.org/abs/1806.04548)

##### PDF
[http://arxiv.org/pdf/1806.04548](http://arxiv.org/pdf/1806.04548)

