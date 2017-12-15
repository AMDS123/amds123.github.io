---
layout: post
title: "Deep Learning the Indus Script"
date: 2017-02-02 01:56:22
categories: arXiv_SD
tags: arXiv_SD CNN Deep_Learning
author: Satish Palaniappan, Ronojoy Adhikari
mathjax: true
---

* content
{:toc}

##### Abstract
Standardized corpora of undeciphered scripts, a necessary starting point for computational epigraphy, requires laborious human effort for their preparation from raw archaeological records. Automating this process through machine learning algorithms can be of significant aid to epigraphical research. Here, we take the first steps in this direction and present a deep learning pipeline that takes as input images of the undeciphered Indus script, as found in archaeological artifacts, and returns as output a string of graphemes, suitable for inclusion in a standard corpus. The image is first decomposed into regions using Selective Search and these regions are classified as containing textual and/or graphical information using a convolutional neural network. Regions classified as potentially containing text are hierarchically merged and trimmed to remove non-textual information. The remaining textual part of the image is segmented using standard image processing techniques to isolate individual graphemes. This set is finally passed to a second convolutional neural network to classify the graphemes, based on a standard corpus. The classifier can identify the presence or absence of the most frequent Indus grapheme, the "jar" sign, with an accuracy of 92%. Our results demonstrate the great potential of deep learning approaches in computational epigraphy and, more generally, in the digital humanities.

##### Abstract (translated by Google)
未加密文本的标准化语料库是计算金石的一个必要的起点，需要费力的人力才能从原始的考古记录中进行准备。通过机器学习算法实现这个过程的自动化可以对书写研究有重要的帮助。在这里，我们在这个方向上迈出了第一步，展示了一个深度的学习流程，将考古文物中发现的印度梧桐脚本作为输入图像，并作为输出返回一个适合列入标准语料库的字符串。首先使用选择性搜索将图像分解成区域，并使用卷积神经网络将这些区域分类为包含文本和/或图形信息。被分类为可能包含文本的区域被分层合并和裁剪以去除非文本信息。图像的剩余文本部分使用标准的图像处理技术来分割以隔离单独的字形。这个集合最终传递到第二个卷积神经网络，根据标准语料库对字形进行分类。分类器可以确定是否存在最频繁的印度语字形，“瓶子”的标志，准确率为92％。我们的研究结果证明了深度学习方法在计算金石学，更普遍的数字人文学的巨大潜力。

##### URL
[https://arxiv.org/abs/1702.00523](https://arxiv.org/abs/1702.00523)

##### PDF
[https://arxiv.org/pdf/1702.00523](https://arxiv.org/pdf/1702.00523)

