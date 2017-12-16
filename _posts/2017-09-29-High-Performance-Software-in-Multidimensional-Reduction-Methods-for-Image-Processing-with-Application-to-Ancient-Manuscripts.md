---
layout: post
title: "High Performance Software in Multidimensional Reduction Methods for Image Processing with Application to Ancient Manuscripts"
date: 2017-09-29 17:58:37
categories: arXiv_CV
tags: arXiv_CV
author: Corneliu T.C. Arsene, Peter E. Pormann, Naima Afif, Stephen Church, Mark Dickinson
mathjax: true
---

* content
{:toc}

##### Abstract
Multispectral imaging is an important technique for improving the readability of written or printed text where the letters have faded, either due to deliberate erasing or simply due to the ravages of time. Often the text can be read simply by looking at individual wavelengths, but in some cases the images need further enhancement to maximise the chances of reading the text. There are many possible enhancement techniques and this paper assesses and compares an extended set of dimensionality reduction methods for image processing. We assess 15 dimensionality reduction methods in two different manuscripts. This assessment was performed both subjectively by asking the opinions of scholars who were experts in the languages used in the manuscripts which of the techniques they preferred and also by using the Davies-Bouldin and Dunn indexes for assessing the quality of the resulted image clusters. We found that the Canonical Variates Analysis (CVA) method which was using a Matlab implementation and we have used previously to enhance multispectral images, it was indeed superior to all the other tested methods. However it is very likely that other approaches will be more suitable in specific circumstance so we would still recommend that a range of these techniques are tried. In particular, CVA is a supervised clustering technique so it requires considerably more user time and effort than a non-supervised technique such as the much more commonly used Principle Component Analysis Approach (PCA). If the results from PCA are adequate to allow a text to be read then the added effort required for CVA may not be justified. For the purposes of comparing the computational times and the image results, a CVA method is also implemented in C programming language and using the GNU (GNUs Not Unix) Scientific Library (GSL) and the OpenCV (OPEN source Computer Vision) computer vision programming library.

##### Abstract (translated by Google)
多光谱成像是一种重要的技术，用于提高书写或打印文本的可读性，在字母已经消失的情况下，或者由于故意擦除或仅仅由于时间的破坏。通常可以通过查看单个波长来阅读文本，但是在某些情况下，图像需要进一步增强以最大化阅读文本的机会。有许多可能的增强技术，本文评估和比较了一套扩展的降维方法进行图像处理。我们在两个不同的手稿中评估了15个降维方法。这种评估主观上是通过询问在手稿中使用哪种语言的专家的意见，并使用Davies-Bouldin和Dunn指数来评估所得图像簇的质量。我们发现使用Matlab实现的典型变量分析（CVA）方法，我们以前用来增强多光谱图像，它确实优于所有其他测试方法。然而，其他方法很可能在特定情况下更适合，因此我们仍然建议尝试一系列这些技术。特别是，CVA是一种有监督的聚类技术，因此与非监督技术（比如更常用的主成分分析法（PCA））相比，它需要更多的用户时间和精力。如果PCA的结果足以允许读取文本，则CVA所需的额外努力可能是不合理的。为了比较计算时间和图像结果，还使用C语言编程语言，并使用GNU（GNU非Unix）科学库（GSL）和OpenCV（OPEN源计算机视觉）计算机视觉编程库。

##### URL
[https://arxiv.org/abs/1612.06457](https://arxiv.org/abs/1612.06457)

##### PDF
[https://arxiv.org/pdf/1612.06457](https://arxiv.org/pdf/1612.06457)

