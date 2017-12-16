---
layout: post
title: "Deep Photo Style Transfer"
date: 2017-04-11 03:53:28
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Fujun Luan, Sylvain Paris, Eli Shechtman, Kavita Bala
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a deep-learning approach to photographic style transfer that handles a large variety of image content while faithfully transferring the reference style. Our approach builds upon the recent work on painterly transfer that separates style from the content of an image by considering different layers of a neural network. However, as is, this approach is not suitable for photorealistic style transfer. Even when both the input and reference images are photographs, the output still exhibits distortions reminiscent of a painting. Our contribution is to constrain the transformation from the input to the output to be locally affine in colorspace, and to express this constraint as a custom fully differentiable energy term. We show that this approach successfully suppresses distortion and yields satisfying photorealistic style transfers in a broad variety of scenarios, including transfer of the time of day, weather, season, and artistic edits.

##### Abstract (translated by Google)
本文介绍了一种摄影风格转换的深度学习方法，处理大量的图像内容，同时忠实地传递参考风格。我们的方法建立在最近的绘画转移工作上，通过考虑不同层次的神经网络，将风格与图像的内容分开。但是，这种方法不适用于照片级的风格转换。即使输入图像和参考图像都是照片，输出仍会呈现让人联想到绘画的变形。我们的贡献是限制从输入到输出的转换，在色彩空间中局部仿射，并将这个约束表达为一个自定义的完全可微能量项。我们表明，这种方法成功地抑制了扭曲，并在广泛的场景中产生令人满意的逼真风格的转换，包括时间，天气，季节和艺术编辑的转移。

##### URL
[https://arxiv.org/abs/1703.07511](https://arxiv.org/abs/1703.07511)

##### PDF
[https://arxiv.org/pdf/1703.07511](https://arxiv.org/pdf/1703.07511)

