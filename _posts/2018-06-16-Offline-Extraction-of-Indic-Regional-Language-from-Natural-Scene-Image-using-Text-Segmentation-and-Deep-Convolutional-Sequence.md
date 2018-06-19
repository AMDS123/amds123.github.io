---
layout: post
title: "Offline Extraction of Indic Regional Language from Natural Scene Image using Text Segmentation and Deep Convolutional Sequence"
date: 2018-06-16 08:31:06
categories: arXiv_AI
tags: arXiv_AI Object_Detection Segmentation CNN RNN Deep_Learning Detection Recognition
author: Sauradip Nag, Pallab Kumar Ganguly, Sumit Roy, Sourab Jha, Krishna Bose, Abhishek Jha, Koushik Dasgupta
mathjax: true
---

* content
{:toc}

##### Abstract
Regional language extraction from a natural scene image is always a challenging proposition due to its dependence on the text information extracted from Image. Text Extraction on the other hand varies on different lighting condition, arbitrary orientation, inadequate text information, heavy background influence over text and change of text appearance. This paper presents a novel unified method for tackling the above challenges. The proposed work uses an image correction and segmentation technique on the existing Text Detection Pipeline an Efficient and Accurate Scene Text Detector (EAST). EAST uses standard PVAnet architecture to select features and non maximal suppression to detect text from image. Text recognition is done using combined architecture of MaxOut convolution neural network (CNN) and Bidirectional long short term memory (LSTM) network. After recognizing text using the Deep Learning based approach, the native Languages are translated to English and tokenized using standard Text Tokenizers. The tokens that very likely represent a location is used to find the Global Positioning System (GPS) coordinates of the location and subsequently the regional languages spoken in that location is extracted. The proposed method is tested on a self generated dataset collected from Government of India dataset and experimented on Standard Dataset to evaluate the performance of the proposed technique. Comparative study with a few state-of-the-art methods on text detection, recognition and extraction of regional language from images shows that the proposed method outperforms the existing methods.

##### Abstract (translated by Google)
从自然场景图像提取区域语言总是一个具有挑战性的命题，因为它依赖于从图像中提取的文本信息。另一方面，文本提取根据不同的照明条件，任意方向，不足的文本信息，背景对文本的重大影响以及文本外观的改变而变化。本文提出了一种新的统一方法来应对上述挑战。所提出的工作在现有的文本检测流水线上使用图像校正和分割技术，即高效且准确的场景文本检测器（EAST）。 EAST使用标准PVAnet架构来选择特征和非最大抑制来检测图像中的文本。文本识别使用MaxOut卷积神经网络（CNN）和双向长期短期记忆（LSTM）网络的组合体系结构完成。使用基于深度学习的方法识别文本后，本地语言被翻译成英文，并使用标准文本标记器进行标记。很可能代表位置的令牌用于查找位置的全球定位系统（GPS）坐标，并随后提取在该位置说出的区域语言。所提出的方法在从印度政府数据集收集的自生数据集上进行测试，并在标准数据集上进行实验以评估所提出的技术的性能。用几种最先进的方法进行文本检测，识别和从图像中提取区域语言的比较研究表明，所提出的方法优于现有方法。

##### URL
[http://arxiv.org/abs/1806.06208](http://arxiv.org/abs/1806.06208)

##### PDF
[http://arxiv.org/pdf/1806.06208](http://arxiv.org/pdf/1806.06208)

