---
layout: post
title: "r-BTN: Cross-domain Face Composite and Synthesis from Limited Facial Patches"
date: 2017-12-06 20:08:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Transfer_Learning Deep_Learning
author: Yang Song, Zhifei Zhang, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
We start by asking an interesting yet challenging question, "If an eyewitness can only recall the eye features of the suspect, such that the forensic artist can only produce a sketch of the eyes (e.g., the top-left sketch shown in Fig. 1), can advanced computer vision techniques help generate the whole face image?" A more generalized question is that if a large proportion (e.g., more than 50%) of the face/sketch is missing, can a realistic whole face sketch/image still be estimated. Existing face completion and generation methods either do not conduct domain transfer learning or can not handle large missing area. For example, the inpainting approach tends to blur the generated region when the missing area is large (i.e., more than 50%). In this paper, we exploit the potential of deep learning networks in filling large missing region (e.g., as high as 95% missing) and generating realistic faces with high-fidelity in cross domains. We propose the recursive generation by bidirectional transformation networks (r-BTN) that recursively generates a whole face/sketch from a small sketch/face patch. The large missing area and the cross domain challenge make it difficult to generate satisfactory results using a unidirectional cross-domain learning structure. On the other hand, a forward and backward bidirectional learning between the face and sketch domains would enable recursive estimation of the missing region in an incremental manner (Fig. 1) and yield appealing results. r-BTN also adopts an adversarial constraint to encourage the generation of realistic faces/sketches. Extensive experiments have been conducted to demonstrate the superior performance from r-BTN as compared to existing potential solutions.

##### Abstract (translated by Google)
我们首先提出一个有趣而富有挑战性的问题：“如果目击者只能回想起犯罪嫌疑人的眼睛特征，法医就只能产生一个眼睛的草图（例如，图1中的左上角草图），高级计算机视觉技术能够帮助生成整个脸部图像吗？一个更普遍的问题是如果面部/素描的很大比例（例如超过50％）缺失，那么仍然可以估计真实的全脸素描/图像。现有的面部完成和生成方法要么不进行域名转移学​​习，要么不能处理大面积的缺失区域。例如，当缺失面积大（即，超过50％）时，修复方法倾向于使生成的区域模糊。在本文中，我们利用深度学习网络的潜力来填充大的缺失区域（例如高达95％的缺失），并在交叉领域中生成具有高保真度的逼真面部。我们提出递归生成的双向变换网络（r-BTN），递归地从一个小的草图/面片生成一个完整的脸部/草图。大的缺失区域和跨域挑战使得使用单向跨域学习结构难以产生令人满意的结果。另一方面，面和草图域之间的向前和向后的双向学习将使得递增地估计丢失区域（图1）并产生有吸引力的结果。 r-BTN也采取对抗性的限制来鼓励生成逼真的面孔/草图。已经进行了大量的实验来证明r-BTN与现有的潜在解决方案相比的优越性能。

##### URL
[http://arxiv.org/abs/1706.00556](http://arxiv.org/abs/1706.00556)

##### PDF
[http://arxiv.org/pdf/1706.00556](http://arxiv.org/pdf/1706.00556)

