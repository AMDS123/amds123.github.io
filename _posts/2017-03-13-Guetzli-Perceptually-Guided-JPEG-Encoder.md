---
layout: post
title: "Guetzli: Perceptually Guided JPEG Encoder"
date: 2017-03-13 14:40:08
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jyrki Alakuijala, Robert Obryk, Ostap Stoliarchuk, Zoltan Szabadka, Lode Vandevenne, Jan Wassenberg
mathjax: true
---

* content
{:toc}

##### Abstract
Guetzli is a new JPEG encoder that aims to produce visually indistinguishable images at a lower bit-rate than other common JPEG encoders. It optimizes both the JPEG global quantization tables and the DCT coefficient values in each JPEG block using a closed-loop optimizer. Guetzli uses Butteraugli, our perceptual distance metric, as the source of feedback in its optimization process. We reach a 29-45% reduction in data size for a given perceptual distance, according to Butteraugli, in comparison to other compressors we tried. Guetzli's computation is currently extremely slow, which limits its applicability to compressing static content and serving as a proof- of-concept that we can achieve significant reductions in size by combining advanced psychovisual models with lossy compression techniques.

##### Abstract (translated by Google)
Guetzli是一种新的JPEG编码器，其目的是以比其他常见的JPEG编码器更低的比特率产生视觉上不可区分的图像。它使用闭环优化器优化每个JPEG块中的JPEG全局量化表和DCT系数值。 Guetzli使用Butteraugli（我们的感知距离度量）作为其优化过程中反馈的来源。按照Butteraugli的说法，与我们试用的其他压缩机相比，在给定的感知距离上数据量减少了29-45％。 Guetzli的计算速度目前非常缓慢，这限制了它在压缩静态内容方面的适用性，并且作为一个概念验证，我们可以通过将先进的心理视觉模型与有损压缩技术相结合来实现显着的尺寸缩小。

##### URL
[https://arxiv.org/abs/1703.04421](https://arxiv.org/abs/1703.04421)

##### PDF
[https://arxiv.org/pdf/1703.04421](https://arxiv.org/pdf/1703.04421)

