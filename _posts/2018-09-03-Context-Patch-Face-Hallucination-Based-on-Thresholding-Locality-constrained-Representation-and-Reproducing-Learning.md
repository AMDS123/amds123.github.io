---
layout: post
title: "Context-Patch Face Hallucination Based on Thresholding Locality-constrained Representation and Reproducing Learning"
date: 2018-09-03 17:23:38
categories: arXiv_CV
tags: arXiv_CV Knowledge Face
author: Junjun Jiang, Yi Yu, Suhua Tang, Jiayi Ma, Akiko Aizawa, Kiyoharu Aizawa
mathjax: true
---

* content
{:toc}

##### Abstract
Face hallucination is a technique that reconstruct high-resolution (HR) faces from low-resolution (LR) faces, by using the prior knowledge learned from HR/LR face pairs. Most state-of-the-arts leverage position-patch prior knowledge of human face to estimate the optimal representation coefficients for each image patch. However, they focus only the position information and usually ignore the context information of image patch. In addition, when they are confronted with misalignment or the Small Sample Size (SSS) problem, the hallucination performance is very poor. To this end, this study incorporates the contextual information of image patch and proposes a powerful and efficient context-patch based face hallucination approach, namely Thresholding Locality-constrained Representation and Reproducing learning (TLcR-RL). Under the context-patch based framework, we advance a thresholding based representation method to enhance the reconstruction accuracy and reduce the computational complexity. To further improve the performance of the proposed algorithm, we propose a promotion strategy called reproducing learning. By adding the estimated HR face to the training set, which can simulates the case that the HR version of the input LR face is present in the training set, thus iteratively enhancing the final hallucination result. Experiments demonstrate that the proposed TLcR-RL method achieves a substantial increase in the hallucinated results, both subjectively and objectively. Additionally, the proposed framework is more robust to face misalignment and the SSS problem, and its hallucinated HR face is still very good when the LR test face is from the real-world. The MATLAB source code is available at https://github.com/junjun-jiang/TLcR-RL

##### Abstract (translated by Google)
面部幻觉是一种通过使用从HR / LR面部对获得的先验知识从低分辨率（LR）面重建高分辨率（HR）面部的技术。大多数现有技术利用位置补丁人脸的先验知识来估计每个图像块的最佳表示系数。但是，它们只关注位置信息，通常忽略图像补丁的上下文信息。此外，当他们遇到错位或小样本量（SSS）问题时，幻觉表现非常差。为此，本研究结合了图像补丁的上下文信息，并提出了一种强大而有效的基于上下文补丁的面部幻觉方法，即阈值局部约束表示和再现学习（TLcR-RL）。在基于上下文补丁的框架下，我们提出了一种基于阈值的表示方法，以提高重建精度并降低计算复杂度。为了进一步提高所提算法的性能，我们提出了一种称为再生学习的推广策略。通过将估计的HR面部添加到训练集，其可以模拟输入LR面部的HR版本存在于训练集中的情况，从而迭代地增强最终的幻觉结果。实验证明，所提出的TLcR-RL方法在主观和客观上实现了幻觉结果的显着增加。此外，所提出的框架对于面对错位和SSS问题更加健壮，并且当LR测试面来自现实世界时，其幻觉HR面部仍然非常好。 MATLAB源代码可从https://github.com/junjun-jiang/TLcR-RL获得

##### URL
[http://arxiv.org/abs/1809.00665](http://arxiv.org/abs/1809.00665)

##### PDF
[http://arxiv.org/pdf/1809.00665](http://arxiv.org/pdf/1809.00665)

