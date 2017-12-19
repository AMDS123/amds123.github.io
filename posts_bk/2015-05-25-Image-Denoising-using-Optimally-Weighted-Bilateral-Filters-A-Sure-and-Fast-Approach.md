---
layout: post
title: "Image Denoising using Optimally Weighted Bilateral Filters: A Sure and Fast Approach"
date: 2015-05-25 09:42:04
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Kunal N. Chaudhury, Kollipara Rithwik
mathjax: true
---

* content
{:toc}

##### Abstract
The bilateral filter is known to be quite effective in denoising images corrupted with small dosages of additive Gaussian noise. The denoising performance of the filter, however, is known to degrade quickly with the increase in noise level. Several adaptations of the filter have been proposed in the literature to address this shortcoming, but often at a substantial computational overhead. In this paper, we report a simple pre-processing step that can substantially improve the denoising performance of the bilateral filter, at almost no additional cost. The modified filter is designed to be robust at large noise levels, and often tends to perform poorly below a certain noise threshold. To get the best of the original and the modified filter, we propose to combine them in a weighted fashion, where the weights are chosen to minimize (a surrogate of) the oracle mean-squared-error (MSE). The optimally-weighted filter is thus guaranteed to perform better than either of the component filters in terms of the MSE, at all noise levels. We also provide a fast algorithm for the weighted filtering. Visual and quantitative denoising results on standard test images are reported which demonstrate that the improvement over the original filter is significant both visually and in terms of PSNR. Moreover, the denoising performance of the optimally-weighted bilateral filter is competitive with the computation-intensive non-local means filter.

##### Abstract (translated by Google)
已知双边滤波器对用小剂量的加性高斯噪声破坏的图像进行去噪是非常有效的。然而，已知过滤器的降噪性能随着噪声水平的增加而迅速降低。为了解决这个缺点，文献中已经提出了一些滤波器的改进，但是通常在相当大的计算开销上。在本文中，我们报告了一个简单的预处理步骤，可以显着提高双边滤波器的去噪性能，几乎不需要额外的成本。改进的滤波器被设计成在较大的噪声水平下是鲁棒的，并且经常往往在低于某个噪声阈值时表现不佳。为了得到最好的原始的和修改后的滤波器，我们建议将它们加权组合，其中权重被选择为使甲骨文平均平方误差（MSE）的（代替）最小化。因此，在所有噪声水平下，最佳加权滤波器在MSE方面保证比任一个分量滤波器更好地执行。我们还为加权滤波提供了一个快速算法。在标准测试图像上的视觉和定量去噪结果被报告，其证明对原始过滤器的改进在视觉上和在PSNR方面都是显着的。此外，最优加权双边滤波器的去噪性能与计算密集型非局部均值滤波器相当。

##### URL
[https://arxiv.org/abs/1505.00074](https://arxiv.org/abs/1505.00074)

##### PDF
[https://arxiv.org/pdf/1505.00074](https://arxiv.org/pdf/1505.00074)

