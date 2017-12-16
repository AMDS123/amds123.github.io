---
layout: post
title: "Date-Field Retrieval in Scene Image and Video Frames using Text Enhancement and Shape Coding"
date: 2017-07-21 10:45:00
categories: arXiv_CV
tags: arXiv_CV OCR Recognition
author: Partha Pratim Roy, Ayan Kumar Bhunia, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Text recognition in scene image and video frames is difficult because of low resolution, blur, background noise, etc. Since traditional OCRs do not perform well in such images, information retrieval using keywords could be an alternative way to index/retrieve such text information. Date is a useful piece of information which has various applications including date-wise videos/scene searching, indexing or retrieval. This paper presents a date spotting based information retrieval system for natural scene image and video frames where text appears with complex backgrounds. We propose a line based date spotting approach using Hidden Markov Model (HMM) which is used to detect the date information in a given text. Different date models are searched from a line without segmenting characters or words. Given a text line image in RGB, we apply an efficient gray image conversion to enhance the text information. Wavelet decomposition and gradient sub-bands are used to enhance text information in gray scale. Next, Pyramid Histogram of Oriented Gradient (PHOG) feature has been extracted from gray image and binary images for date-spotting framework. Binary and gray image features are combined by MLP based Tandem approach. Finally, to boost the performance further, a shape coding based scheme is used to combine the similar shape characters in same class during word spotting. For our experiment, three different date models have been constructed to search similar date information having numeric dates that contains numeral values and punctuations and semi-numeric that contains dates with numerals along with months in scene/video text. We have tested our system on 1648 text lines and the results show the effectiveness of our proposed date spotting approach.

##### Abstract (translated by Google)
由于低分辨率，模糊，背景噪声等，在场景图像和视频帧中的文本识别是困难的。由于传统的OCR在这样的图像中不能很好地执行，使用关键字的信息检索可以是索引/检索这种文本信息的替代方式。日期是一个有用的信息，它有各种应用程序，包括日期明智的视频/场景搜索，索引或检索。本文提出了一种基于日期识别的自然场景图像和背景复杂文本的视频帧信息检索系统。我们提出了一种基于线的日期识别方法，使用隐马尔可夫模型（HMM）来检测给定文本中的日期信息。从一行中搜索不同的日期模型，而不分割字符或单词。给定RGB中的文本行图像，我们应用高效的灰度图像转换来增强文本信息。小波分解和梯度子带用于增强灰度级的文本信息。接下来，从灰度图像和二值图像中提取金字塔倾斜梯度直方图（PHOG）特征用于日期识别框架。二进制和灰度图像特征通过基于MLP的串联方法相结合。最后，为了进一步提高性能，采用基于形状编码的方案在字词识别过程中将同类形状字符进行组合。对于我们的实验，已经构建了三种不同的日期模型来搜索具有包含数字值和标点符号的数字日期的相似日期信息，并且在场景/视频文本中搜索包含数字和月份的日期的半数字。我们已经在1648条文本行上测试了我们的系统，结果显示了我们建议的日期识别方法的有效性。

##### URL
[https://arxiv.org/abs/1707.06833](https://arxiv.org/abs/1707.06833)

##### PDF
[https://arxiv.org/pdf/1707.06833](https://arxiv.org/pdf/1707.06833)

