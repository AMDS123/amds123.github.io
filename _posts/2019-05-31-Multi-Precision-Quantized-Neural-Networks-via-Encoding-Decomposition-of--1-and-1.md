---
layout: post
title: "Multi-Precision Quantized Neural Networks via Encoding Decomposition of -1 and +1"
date: 2019-05-31 02:49:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Qigong Sun, Fanhua Shang, Kang Yang, Xiufang Li, Yan Ren, Licheng Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
The training of deep neural networks (DNNs) requires intensive resources both for computation and for storage performance. Thus, DNNs cannot be efficiently applied to mobile phones and embedded devices, which seriously limits their applicability in industry applications. To address this issue, we propose a novel encoding scheme of using {-1,+1} to decompose quantized neural networks (QNNs) into multi-branch binary networks, which can be efficiently implemented by bitwise operations (xnor and bitcount) to achieve model compression, computational acceleration and resource saving. Based on our method, users can easily achieve different encoding precisions arbitrarily according to their requirements and hardware resources. The proposed mechanism is very suitable for the use of FPGA and ASIC in terms of data storage and computation, which provides a feasible idea for smart chips. We validate the effectiveness of our method on both large-scale image classification tasks (e.g., ImageNet) and object detection tasks. In particular, our method with low-bit encoding can still achieve almost the same performance as its full-precision counterparts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13389](http://arxiv.org/abs/1905.13389)

##### PDF
[http://arxiv.org/pdf/1905.13389](http://arxiv.org/pdf/1905.13389)

