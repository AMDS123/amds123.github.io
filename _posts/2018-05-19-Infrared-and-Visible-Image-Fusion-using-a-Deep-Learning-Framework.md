---
layout: post
title: "Infrared and Visible Image Fusion using a Deep Learning Framework"
date: 2018-05-19 08:45:41
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hui Li, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning has become a very active research tool which is used in many image processing fields. In this paper, we propose an effective image fusion method using a deep learning framework to generate a single image which contains all the features from infrared and visible images. First, the source images are decomposed into base parts and detail content. Then the base parts are fused by weighted-averaging. For the detail content, we use a deep learning network to extract multi-layer features. Using these features, we use l_1-norm and weighted-average strategy to generate several candidates of the fused detail content. Once we get these candidates, the max selection strategy is used to get final fused detail content. Finally, the fused image will be reconstructed by combining the fused base part and detail content. The experimental results demonstrate that our proposed method achieves state-of-the-art performance in both objective assessment and visual quality. The Code of our fusion method is available at https://github.com/exceptionLi/imagefusion_deeplearning

##### Abstract (translated by Google)
近年来，深度学习已成为许多图像处理领域中非常活跃的研究工具。在本文中，我们提出了一种有效的图像融合方法，使用深度学习框架来生成包含红外和可见图像的所有特征的单个图像。首先，将源图像分解为基本部分和详细内容。然后基础部分通过加权平均来融合。对于细节内容，我们使用深度学习网络来提取多层功能。使用这些特征，我们使用l_1范数和加权平均策略来生成多个融合细节内容的候选项。一旦我们得到这些候选人，最大选择策略就用来获得最终的融合细节内容。最后，通过融合基础部分和细节内容来重构融合图像。实验结果表明，我们提出的方法在客观评估和视觉质量方面都达到了最先进的性能。我们的融合方法的代码可以在https://github.com/exceptionLi/imagefusion_deeplearning中找到

##### URL
[http://arxiv.org/abs/1804.06992](http://arxiv.org/abs/1804.06992)

##### PDF
[http://arxiv.org/pdf/1804.06992](http://arxiv.org/pdf/1804.06992)

