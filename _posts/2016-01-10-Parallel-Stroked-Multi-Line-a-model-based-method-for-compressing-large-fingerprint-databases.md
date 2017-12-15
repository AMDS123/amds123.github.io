---
layout: post
title: "Parallel Stroked Multi Line: a model-based method for compressing large fingerprint databases"
date: 2016-01-10 15:01:10
categories: arXiv_CV
tags: arXiv_CV
author: Hamid Mansouri (Machine Vision Lab., Computer Engineering Department, Ferdowsi University of Mashhad, Mashhad, Iran), Hamid-Reza Pourreza (Machine Vision Lab., Computer Engineering Department, Ferdowsi University of Mashhad, Mashhad, Iran)
mathjax: true
---

* content
{:toc}

##### Abstract
With increasing usage of fingerprints as an important biometric data, the need to compress the large fingerprint databases has become essential. The most recommended compression algorithm, even by standards, is JPEG2K. But at high compression rates, this algorithm is ineffective. In this paper, a model is proposed which is based on parallel lines with same orientations, arbitrary widths and same gray level values located on rectangle with constant gray level value as background. We refer to this algorithm as Parallel Stroked Multi Line (PSML). By using Adaptive Geometrical Wavelet and employing PSML, a compression algorithm is developed. This compression algorithm can preserve fingerprint structure and minutiae. The exact algorithm of computing the PSML model take exponential time. However, we have proposed an alternative approximation algorithm, which reduces the time complexity to $O(n^3)$. The proposed PSML alg. has significant advantage over Wedgelets Transform in PSNR value and visual quality in compressed images. The proposed method, despite the lower PSNR values than JPEG2K algorithm in common range of compression rates, in all compression rates have nearly equal or greater advantage over JPEG2K when used by Automatic Fingerprint Identification Systems (AFIS). At high compression rates, according to PSNR values, mean EER rate and visual quality, the encoded images with JPEG2K can not be identified from each other after compression. But, images encoded by the PSML alg. retained the sufficient information to maintain fingerprint identification performances similar to the ones obtained by raw images without compression. One the U.are.U 400 database, the mean EER rate for uncompressed images is 4.54%, while at 267:1 compression ratio, this value becomes 49.41% and 6.22% for JPEG2K and PSML, respectively. This result shows a significant improvement over the standard JPEG2K algorithm.

##### Abstract (translated by Google)
随着指纹作为重要生物特征数据的使用增加，需要压缩大型指纹数据库变得至关重要。最推荐的压缩算法，即使是标准，也是JPEG2K。但是在高压缩率下，这个算法是无效的。本文提出了一种以灰度值恒定的矩形为背景，以相同方向，任意宽度，相同灰度值的平行线为基础的模型。我们把这个算法称为平行描边多线（PSML）。通过使用自适应几何小波和采用PSML，开发了一种压缩算法。这种压缩算法可以保留指纹结构和细节。计算PSML模型的确切算法采用指数时间。然而，我们已经提出了另一个近似算法，它将时间复杂度降低到$ O（n ^ 3）$。建议的PSML alg。在压缩图像的PSNR值和视觉质量上比Wedgelets变换具有显着的优势。在自动指纹识别系统（Automatic Fingerprint Identification Systems，AFIS）使用的方法中，尽管在普通的压缩率范围内PSNR值低于JPEG2K算法，但在所有的压缩率上都优于JPEG2K。在压缩率较高的情况下，根据PSNR值，平均EER率和视觉质量，JPEG2K编码后的图像压缩后无法相互识别。但是，由PSML alg编码的图像。保留足够的信息以维持与未经压缩的原始图像获得的类似的指纹识别性能。 U.are.U 400数据库中，未压缩图像的平均EER率为4.54％，而在267：1压缩比下，JPEG2K和PSML的平均EER率分别为49.41％和6.22％。这个结果显示了比标准的JPEG2K算法显着的改进。

##### URL
[https://arxiv.org/abs/1601.02225](https://arxiv.org/abs/1601.02225)

##### PDF
[https://arxiv.org/pdf/1601.02225](https://arxiv.org/pdf/1601.02225)

