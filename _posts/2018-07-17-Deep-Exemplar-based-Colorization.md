---
layout: post
title: "Deep Exemplar-based Colorization"
date: 2018-07-17 17:59:01
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Deep_Learning Quantitative
author: Mingming He, Dongdong Chen, Jing Liao, Pedro V. Sander, Lu Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the first deep learning approach for exemplar-based local colorization. Given a reference color image, our convolutional neural network directly maps a grayscale image to an output colorized image. Rather than using hand-crafted rules as in traditional exemplar-based methods, our end-to-end colorization network learns how to select, propagate, and predict colors from the large-scale data. The approach performs robustly and generalizes well even when using reference images that are unrelated to the input grayscale image. More importantly, as opposed to other learning-based colorization methods, our network allows the user to achieve customizable results by simply feeding different references. In order to further reduce manual effort in selecting the references, the system automatically recommends references with our proposed image retrieval algorithm, which considers both semantic and luminance information. The colorization can be performed fully automatically by simply picking the top reference suggestion. Our approach is validated through a user study and favorable quantitative comparisons to the-state-of-the-art methods. Furthermore, our approach can be naturally extended to video colorization. Our code and models will be freely available for public use.

##### Abstract (translated by Google)
我们提出了第一种基于样本的局部着色的深度学习方法。给定参考彩色图像，我们的卷积神经网络直接将灰度图像映射到输出彩色图像。我们的端到端着色网络不是像传统的基于示例的方法那样使用手工制作的规则，而是学习如何从大规模数据中选择，传播和预测颜色。即使在使用与输入灰度图像无关的参考图像时，该方法也可以很好地执行并且很好地推广。更重要的是，与其他基于学习的着色方法相反，我们的网络允许用户通过简单地提供不同的参考来实现可定制的结果。为了进一步减少选择参考的手动努力，系统自动推荐使用我们提出的图像检索算法的参考，该算法同时考虑语义和亮度信息。只需选择顶部参考建议，就可以完全自动执行着色。我们的方法通过用户研究和对最先进方法的有利定量比较得到验证。此外，我们的方法可以自然地扩展到视频着色。我们的代码和模型将免费供公众使用。

##### URL
[http://arxiv.org/abs/1807.06587](http://arxiv.org/abs/1807.06587)

##### PDF
[http://arxiv.org/pdf/1807.06587](http://arxiv.org/pdf/1807.06587)

