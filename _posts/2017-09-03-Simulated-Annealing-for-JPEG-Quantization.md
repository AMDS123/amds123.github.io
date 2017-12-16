---
layout: post
title: "Simulated Annealing for JPEG Quantization"
date: 2017-09-03 01:10:18
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Max Hopkins, Michael Mitzenmacher, Sebastian Wagner-Carena
mathjax: true
---

* content
{:toc}

##### Abstract
JPEG is one of the most widely used image formats, but in some ways remains surprisingly unoptimized, perhaps because some natural optimizations would go outside the standard that defines JPEG. We show how to improve JPEG compression in a standard-compliant, backward-compatible manner, by finding improved default quantization tables. We describe a simulated annealing technique that has allowed us to find several quantization tables that perform better than the industry standard, in terms of both compressed size and image fidelity. Specifically, we derive tables that reduce the FSIM error by over 10% while improving compression by over 20% at quality level 95 in our tests; we also provide similar results for other quality levels. While we acknowledge our approach can in some images lead to visible artifacts under large magnification, we believe use of these quantization tables, or additional tables that could be found using our methodology, would significantly reduce JPEG file sizes with improved overall image quality.

##### Abstract (translated by Google)
JPEG是使用最广泛的图像格式之一，但在某些方面仍然令人惊讶地未被优化，可能是因为一些自然的优化会超出定义JPEG的标准。我们通过寻找改进的默认量化表来展示如何以符合标准的，向后兼容的方式改进JPEG压缩。我们描述了一个模拟退火技术，它使我们能够在压缩尺寸和图像保真度方面找到几个比行业标准更好的量化表。具体而言，我们推导出在我们的测试中将FSIM误差减少10％以上，同时在质量水平95提高压缩率超过20％的表格;我们也为其他质量水平提供类似的结果。虽然我们承认我们的方法可以在一些图像导致大放大倍率下出现可见的伪像，但是我们相信使用这些量化表或使用我们的方法可以找到的附加表格将显着降低JPEG文件的大小，同时改善整体图像质量。

##### URL
[https://arxiv.org/abs/1709.00649](https://arxiv.org/abs/1709.00649)

##### PDF
[https://arxiv.org/pdf/1709.00649](https://arxiv.org/pdf/1709.00649)

