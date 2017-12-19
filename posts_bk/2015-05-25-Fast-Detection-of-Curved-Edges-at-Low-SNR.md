---
layout: post
title: "Fast Detection of Curved Edges at Low SNR"
date: 2015-05-25 11:47:37
categories: arXiv_CV
tags: arXiv_CV Detection
author: Nati Ofir, Meirav Galun, Boaz Nadler, Ronen Basri
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting edges is a fundamental problem in computer vision with many applications, some involving very noisy images. While most edge detection methods are fast, they perform well only on relatively clean images. Indeed, edges in such images can be reliably detected using only local filters. Detecting faint edges under high levels of noise cannot be done locally at the individual pixel level, and requires more sophisticated global processing. Unfortunately, existing methods that achieve this goal are quite slow. In this paper we develop a novel multiscale method to detect curved edges in noisy images. While our algorithm searches for edges over a huge set of candidate curves, it does so in a practical runtime, nearly linear in the total number of image pixels. As we demonstrate experimentally, our algorithm is orders of magnitude faster than previous methods designed to deal with high noise levels. Nevertheless, it obtains comparable, if not better, edge detection quality on a variety of challenging noisy images.

##### Abstract (translated by Google)
在许多应用中，检测边缘是计算机视觉中的基本问题，其中一些涉及非常嘈杂的图像。虽然大多数边缘检测方法速度很快，但只能在相对干净的图像上才能正常运行实际上，只能使用本地滤波器可靠地检测这些图像中的边缘。在高水平的噪声下检测微弱的边缘不能在单个像素级本地完成，并且需要更复杂的全局处理。不幸的是，实现这一目标的现有方法相当缓慢。在本文中，我们开发了一种新的多尺度方法来检测噪声图像中的弯曲边缘。虽然我们的算法在一大组候选曲线上搜索边缘，但是它在实际的运行时间中这样做，在图像像素的总数中几乎是线性的。正如我们在实验中所展示的那样，我们的算法比以前用于处理高噪声水平的方法快了几个数量级。不过，即使不是更好，它也可以在各种具有挑战性的噪声图像上获得可比较的边缘检测质量。

##### URL
[https://arxiv.org/abs/1505.06600](https://arxiv.org/abs/1505.06600)

##### PDF
[https://arxiv.org/pdf/1505.06600](https://arxiv.org/pdf/1505.06600)

