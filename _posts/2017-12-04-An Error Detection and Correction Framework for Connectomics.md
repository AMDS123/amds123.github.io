---
layout: post
title:  'An Error Detection and Correction Framework for Connectomics'
date:   2017-12-05 19:45:13
categories: arXiv_CV
arXiv_CV 'Detection'
author: Jonathan Zung, Ignacio Tartavull, Kisuk Lee, H. Sebastian Seung
---

* content
{:toc}

##### Abstract
We define and study error detection and correction tasks that are useful for 3D reconstruction of neurons from electron microscopic imagery, and for image segmentation more generally. Both tasks take as input the raw image and a binary mask representing a candidate object. For the error detection task, the desired output is a map of split and merge errors in the object. For the error correction task, the desired output is the true object. We call this object mask pruning, because the candidate object mask is assumed to be a superset of the true object. We train multiscale 3D convolutional networks to perform both tasks. We find that the error-detecting net can achieve high accuracy. The accuracy of the error-correcting net is enhanced if its input object mask is "advice" (union of erroneous objects) from the error-detecting net.

##### Abstract (translated by Google)
我们定义和研究错误检测和纠正任务，这些任务对于电子显微图像中的神经元的三维重建以及更普遍的图像分割是有用的。这两个任务都将原始图像和代表候选对象的二进制掩码作为输入。对于错误检测任务，所需的输出是对象中的拆分和合并错误的映射。对于纠错任务，所需的输出是真实的对象。我们称之为对象遮罩修剪，因为候选对象遮罩被假定为真实对象的超集。我们训练多尺度的三维卷积网络来执行这两个任务。我们发现错误检测网络可以达到很高的精度。如果其输入对象掩码是来自错误检测网络的“建议”（错误对象的联合），则纠错网络的准确性得到增强。

##### URL
[http://arxiv.org/abs/1708.02599](http://arxiv.org/abs/1708.02599)

