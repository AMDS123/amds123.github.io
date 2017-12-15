---
layout: post
title: "Fast algorithms for morphological operations using run-length encoded binary images"
date: 2015-04-04 20:51:43
categories: arXiv_CV
tags: arXiv_CV
author: Gregor Ehrensperger, Alexander Ostermann, Felix Schwitzer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents innovative algorithms to efficiently compute erosions and dilations of run-length encoded (RLE) binary images with arbitrary shaped structuring elements. An RLE image is given by a set of runs, where a run is a horizontal concatenation of foreground pixels. The proposed algorithms extract the skeleton of the structuring element and build distance tables of the input image, which are storing the distance to the next background pixel on the left and right hand sides. This information is then used to speed up the calculations of the erosion and dilation operator by enabling the use of techniques which allow to skip the analysis of certain pixels whenever a hit or miss occurs. Additionally the input image gets trimmed during the preprocessing steps on the base of two primitive criteria. Experimental results show the advantages over other algorithms. The source code of our algorithms is available in C++.

##### Abstract (translated by Google)
本文提出了创新的算法来有效地计算任意形状结构元素的游程编码（RLE）二值图像的糜烂和扩张。 RLE图像由一组运行给出，其中运行是前景像素的水平串联。所提出的算法提取结构化元素的骨架，并建立输入图像的距离表，其存储到左侧和右侧的下一个背景像素的距离。然后通过使用这种技术来加速侵蚀和膨胀算子的计算，该技术允许在发生击中或失误时跳过某些像素的分析。另外，在预处理步骤期间，基于两个原始标准，输入图像被修剪。实验结果显示了优于其他算法的优势。我们的算法的源代码在C ++中可用。

##### URL
[https://arxiv.org/abs/1504.01052](https://arxiv.org/abs/1504.01052)

##### PDF
[https://arxiv.org/pdf/1504.01052](https://arxiv.org/pdf/1504.01052)

