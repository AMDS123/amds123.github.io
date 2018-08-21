---
layout: post
title: "Bitstream-Based JPEG Image Encryption with File-Size Preserving"
date: 2018-08-17 02:37:24
categories: arXiv_CV
tags: arXiv_CV
author: Hiroyuki Kobayashi, Hitoshi Kiya
mathjax: true
---

* content
{:toc}

##### Abstract
An encryption scheme of JPEG images in the bitstream domain is proposed. The proposed scheme preserves the JPEG format even after encrypting the images, and the file size of encrypted images is the exact same as that of the original JPEG images. Several methods for encrypting JPEG images in the bitstream domain have been proposed. However, since some marker codes are generated or lost in the encryption process, the file size of JPEG bitstreams is generally changed due to the encryption operations. The proposed method inputs JPEG bitstreams and selectively encrypts the additional bit components of the Huffman code in the bitstreams. This feature allows us to have encrypted images with the same data size as that recoded in the image transmission process, when JPEG images are replaced with the encrypted ones by the hooking, so that the image transmission are successfully carried out after the hooking.

##### Abstract (translated by Google)
提出了比特流域中JPEG图像的加密方案。即使在加密图像之后，所提出的方案也保留了JPEG格式，并且加密图像的文件大小与原始JPEG图像的文件大小完全相同。已经提出了几种用于在比特流域中加密JPEG图像的方法。然而，由于在加密过程中生成或丢失了一些标记代码，因此JPEG比特流的文件大小通常由于加密操作而改变。所提出的方法输入JPEG比特流并选择性地加密比特流中的霍夫曼码的附加比特分量。此功能允许我们使用与图像传输过程中重新编码的数据大小相同的加密图像，当通过挂钩将JPEG图像替换为加密图像时，可以在挂钩后成功执行图像传输。

##### URL
[http://arxiv.org/abs/1808.06495](http://arxiv.org/abs/1808.06495)

##### PDF
[http://arxiv.org/pdf/1808.06495](http://arxiv.org/pdf/1808.06495)

