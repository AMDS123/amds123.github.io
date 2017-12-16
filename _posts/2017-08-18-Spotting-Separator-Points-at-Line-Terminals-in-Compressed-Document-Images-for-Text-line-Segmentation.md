---
layout: post
title: "Spotting Separator Points at Line Terminals in Compressed Document Images for Text-line Segmentation"
date: 2017-08-18 09:51:17
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Amarnath R, P. Nagabhushan
mathjax: true
---

* content
{:toc}

##### Abstract
Line separators are used to segregate text-lines from one another in document image analysis. Finding the separator points at every line terminal in a document image would enable text-line segmentation. In particular, identifying the separators in handwritten text could be a thrilling exercise. Obviously it would be challenging to perform this in the compressed version of a document image and that is the proposed objective in this research. Such an effort would prevent the computational burden of decompressing a document for text-line segmentation. Since document images are generally compressed using run length encoding (RLE) technique as per the CCITT standards, the first column in the RLE will be a white column. The value (depth) in the white column is very low when a particular line is a text line and the depth could be larger at the point of text line separation. A longer consecutive sequence of such larger depth should indicate the gap between the text lines, which provides the separator region. In case of over separation and under separation issues, corrective actions such as deletion and insertion are suggested respectively. An extensive experimentation is conducted on the compressed images of the benchmark datasets of ICDAR13 and Alireza et al [17] to demonstrate the efficacy.

##### Abstract (translated by Google)
在文档图像分析中，行分隔符用于分隔文本行。在文档图像的每一行终端上查找分隔点将启用文本行分割。特别是在手写文本中识别分隔符可能是一个惊心动魄的练习。显然，在文档图像的压缩版本中执行此操作将是具有挑战性的，这也是本研究提出的目标。这样的努力将防止文本解压缩文本行分割的计算负担。由于通常按照CCITT标准使用运行长度编码（RLE）技术来压缩文档图像，所以RLE中的第一列将是白色列。当某一行是文本行时，白色列中的值（深度）非常低，并且在文本行分隔点处深度可能较大。这种较大深度的较长的连续序列应指示提供分隔符区域的文本行之间的间隙。如果发生超分离和分离问题，分别建议删除和插入等纠正措施。对ICDAR13和Alireza等[17]的基准数据集的压缩图像进行了广泛的实验，以证明其有效性。

##### URL
[https://arxiv.org/abs/1708.05545](https://arxiv.org/abs/1708.05545)

##### PDF
[https://arxiv.org/pdf/1708.05545](https://arxiv.org/pdf/1708.05545)

