---
layout: post
title: "Systholic Boolean Orthonormalizer Network in Wavelet Domain for SAR Image Despeckling"
date: 2016-07-11 16:08:25
categories: arXiv_CV
tags: arXiv_CV
author: Mario Mastriani
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a novel method for removing speckle (in wavelet domain) of unknown variance from SAR images. The me-thod is based on the following procedure: We apply 1) Bidimentional Discrete Wavelet Transform (DWT-2D) to the speckled image, 2) scaling and rounding to the coefficients of the highest subbands (to obtain integer and positive coefficients), 3) bit-slicing to the new highest subbands (to obtain bit-planes), 4) then we apply the Systholic Boolean Orthonormalizer Network (SBON) to the input bit-plane set and we obtain two orthonormal output bit-plane sets (in a Boolean sense), we project a set on the other one, by means of an AND operation, and then, 5) we apply re-assembling, and, 6) re-sca-ling. Finally, 7) we apply Inverse DWT-2D and reconstruct a SAR image from the modified wavelet coefficients. Despeckling results compare favorably to the most of methods in use at the moment.

##### Abstract (translated by Google)
我们描述了一种从SAR图像中去除未知方差的小波域的新方法。该方法基于以下步骤：1）对斑点图像应用1）双向离散小波变换（DWT-2D），2）对最高子带的系数进行缩放和舍入（以获得整数和正系数）， 3）对新的最高子带进行比特分片（得到比特平面），4）然后我们将Systholic布尔正交归一化网络（SBON）应用于输入比特平面集合，并且我们得到两个正交输出比特平面集合一个布尔意义），我们通过一个AND操作来投影另一个集合，然后，5）我们重新组装，6）重新拼凑。最后，7）我们应用逆DWT-2D，并从修改的小波系数重构SAR图像。去斑的结果比目前使用的大多数方法好。

##### URL
[https://arxiv.org/abs/1607.03105](https://arxiv.org/abs/1607.03105)

##### PDF
[https://arxiv.org/pdf/1607.03105](https://arxiv.org/pdf/1607.03105)

