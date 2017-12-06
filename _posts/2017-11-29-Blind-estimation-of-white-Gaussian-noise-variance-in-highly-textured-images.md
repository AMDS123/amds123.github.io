---
layout: post
title: "Blind estimation of white Gaussian noise variance in highly textured images"
date: 2017-11-29 11:43:26
categories: arXiv_CV
tags: arXiv_CV
author: Mykola Ponomarenko, Nikolay Gapon, Viacheslav Voronin, Karen Egiazarian
---

* content
{:toc}

##### Abstract
In the paper, a new method of blind estimation of noise variance in a single highly textured image is proposed. An input image is divided into 8x8 blocks and discrete cosine transform (DCT) is performed for each block. A part of 64 DCT coefficients with lowest energy calculated through all blocks is selected for further analysis. For the DCT coefficients, a robust estimate of noise variance is calculated. Corresponding to the obtained estimate, a part of blocks having very large values of local variance calculated only for the selected DCT coefficients are excluded from the further analysis. These two steps (estimation of noise variance and exclusion of blocks) are iteratively repeated three times. For the verification of the proposed method, a new noise-free test image database TAMPERE17 consisting of many highly textured images is designed. It is shown for this database and different values of noise variance from the set {25, 49, 100, 225}, that the proposed method provides approximately two times lower estimation root mean square error than other methods.

##### Abstract (translated by Google)
本文提出了一种高度纹理图像中噪声方差盲估计的新方法。输入图像被分成8×8块，并对每个块执行离散余弦变换（DCT）。通过所有块计算64个具有最低能量的DCT系数的一部分被选择用于进一步分析。对于DCT系数，计算噪声方差的稳健估计。对应于所获得的估计，从进一步分析中排除仅针对所选DCT系数计算的具有非常大的局部方差值的块的一部分。这两个步骤（估计噪声方差和块的排除）迭代重复三次。为了验证所提出的方法，设计了一个由许多高度纹理图像组成的新的无噪声测试图像数据库TAMPERE17。对于这个数据库以及来自集合{25,49,100,225}的不同噪声方差值，所提出的方法提供的估计均方根误差比其他方法低大约两倍。

##### URL
[https://arxiv.org/abs/1711.10792](https://arxiv.org/abs/1711.10792)

