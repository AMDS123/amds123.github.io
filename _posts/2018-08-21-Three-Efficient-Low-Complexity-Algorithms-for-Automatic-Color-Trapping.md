---
layout: post
title: "Three Efficient, Low-Complexity Algorithms for Automatic Color Trapping"
date: 2018-08-21 19:27:39
categories: arXiv_CV
tags: arXiv_CV
author: Haiyin Wang, Mireille Boutin, Jeffrey Trask, Jan Allebach
mathjax: true
---

* content
{:toc}

##### Abstract
Color separations (most often cyan, magenta, yellow, and black) are commonly used in printing to reproduce multi-color images. For mechanical reasons, these color separations are generally not perfectly aligned with respect to each other when they are rendered by their respective imaging stations. This phenomenon, called color plane misregistration, causes gap and halo artifacts in the printed image. Color trapping is an image processing technique that aims to reduce these artifacts by modifying the susceptible edge boundaries to create small, unnoticeable overlaps between the color planes. We propose three low-complexity algorithms for automatic color trapping which hide the effects of small color plane mis-registrations. Our algorithms are designed for software or embedded firmware implementation. The trapping method they follow is based on a hardware-friendly technique proposed by J. Trask (JTHBCT03) which is too computationally expensive for software or firmware implementation. The first two algorithms are based on the use of look-up tables (LUTs). The first LUT-based algorithm corrects all registration errors of one pixel in extent and reduces several cases of misregistration errors of two pixels in extent using only 727 Kbytes of storage space. This algorithm is particularly attractive for implementation in the embedded firmware of low-cost formatter-based printers. The second LUT-based algorithm corrects all types of misregistration errors of up to two pixels in extent using 3.7 Mbytes of storage space. The third algorithm is a hybrid one that combines LUTs and feature extraction to minimize the storage requirements (724 Kbytes) while still correcting all misregistration errors of up to two pixels in extent. This algorithm is suitable for both embedded firmware implementation on low-cost formatter-based printers and software implementation on host-based printers.

##### Abstract (translated by Google)
分色（通常为青色，品红色，黄色和黑色）通常用于打印以再现多色图像。出于机械原因，当这些分色由它们各自的成像站渲染时，这些分色通常彼此不完全对齐。这种称为彩色平面重合失调的现象在打印图像中引起间隙和光晕伪影。颜色捕获是一种图像处理技术，旨在通过修改易受影响的边缘边界来减少这些伪像，从而在颜色平面之间创建小的，不明显的重叠。我们提出了三种用于自动颜色捕获的低复杂度算法，它们隐藏了小颜色平面错误配准的影响。我们的算法专为软件或嵌入式固件实现而设计。他们遵循的陷印方法基于J.Trask（JTHBCT03）提出的硬件友好技术，其对于软件或固件实现而言计算成本太高。前两种算法基于查找表（LUT）的使用。第一个基于LUT的算法校正了范围内一个像素的所有配准误差，并且仅使用727千字节的存储空间减少了范围内两个像素的误配准错误的几种情况。该算法对于在基于低成本格式器的打印机的嵌入式固件中的实现特别有吸引力。第二种基于LUT的算法使用3.7 MB的存储空间来纠正范围内最多两个像素的所有类型的重合失调错误。第三种算法是混合算法，它结合了LUT和特征提取，以最小化存储要求（724千字节），同时仍然纠正范围内最多两个像素的所有重合失调错误。该算法适用于基于低成本格式化器的打印机上的嵌入式固件实现和基于主机的打印机上的软件实现。

##### URL
[http://arxiv.org/abs/1808.07096](http://arxiv.org/abs/1808.07096)

##### PDF
[http://arxiv.org/pdf/1808.07096](http://arxiv.org/pdf/1808.07096)

