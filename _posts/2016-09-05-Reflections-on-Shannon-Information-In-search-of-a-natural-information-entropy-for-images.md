---
layout: post
title: "Reflections on Shannon Information: In search of a natural information-entropy for images"
date: 2016-09-05 11:59:47
categories: arXiv_CV
tags: arXiv_CV Relation
author: Kieran G. Larkin
mathjax: true
---

* content
{:toc}

##### Abstract
It is not obvious how to extend Shannon's original information entropy to higher dimensions, and many different approaches have been tried. We replace the English text symbol sequence originally used to illustrate the theory by a discrete, bandlimited signal. Using Shannon's later theory of sampling we derive a new and symmetric version of the second order entropy in 1D. The new theory then naturally extends to 2D and higher dimensions, where by naturally we mean simple, symmetric, isotropic and parsimonious. Simplicity arises from the direct application of Shannon's joint entropy equalities and inequalities to the gradient (del) vector field image embodying the second order relations of the scalar image. Parsimony is guaranteed by halving of the vector data rate using Papoulis' generalized sampling expansion. The new 2D entropy measure, which we dub delentropy, is underpinned by a computable probability density function we call deldensity. The deldensity captures the underlying spatial image structure and pixel co-occurrence. It achieves this because each scalar image pixel value is nonlocally related to the entire gradient vector field. Both deldensity and delentropy are highly tractable and yield many interesting connections and useful inequalities. The new measure explicitly defines a realizable encoding algorithm and a corresponding reconstruction. Initial tests show that delentropy compares favourably with the conventional intensity-based histogram entropy and the compressed data rates of lossless image encoders (GIF, PNG, WEBP, JP2K-LS and JPG-LS) for a selection of images. The symmetric approach may have applications to higher dimensions and problems concerning image complexity measures.

##### Abstract (translated by Google)
如何将Shannon的原始信息熵扩展到更高的维度并不是很明显，并且尝试了许多不同的方法。我们用一个离散的带限信号取代最初用于说明理论的英文文本符号序列。使用香农后来的抽样理论，我们推导出一维中二阶熵的新对称版本。然后，新的理论自然延伸到二维和更高的维度，自然地，我们指的是简单的，对称的，各向同性的和简约的。由于将Shannon的联合熵平等和不等式直接应用于体现标量图像的二阶关系的梯度（del）矢量场图像，所以简单起来。通过使用Papoulis的广义采样扩展将矢量数据速率减半来保证简约性。新的二维熵度量，我们称之为delentropy，是由一个可计算的概率密度函数，我们称为密度。 deldensity捕捉潜在的空间图像结构和像素共现。由于每个标量图像像素值都与整个梯度矢量场非局部相关，因此可以实现这一点。隐密和绝对是非常易于处理的，并产生许多有趣的联系和有用的不平等。新措施明确定义了可实现的编码算法和相应的重构。初步测试表明，与常规的基于强度的直方图熵和无损图像编码器（GIF，PNG，WEBP，JP2K-LS和JPG-LS）的压缩数据速率相比，去卷积与图像选择相比有利。对称方法可以应用于更高维度和与图像复杂度测量有关的问题。

##### URL
[https://arxiv.org/abs/1609.01117](https://arxiv.org/abs/1609.01117)

##### PDF
[https://arxiv.org/pdf/1609.01117](https://arxiv.org/pdf/1609.01117)

