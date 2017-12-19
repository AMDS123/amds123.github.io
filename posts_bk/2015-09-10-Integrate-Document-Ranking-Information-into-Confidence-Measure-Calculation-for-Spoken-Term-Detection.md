---
layout: post
title: "Integrate Document Ranking Information into Confidence Measure Calculation for Spoken Term Detection"
date: 2015-09-10 09:01:35
categories: arXiv_CL
tags: arXiv_CL Detection
author: Quan Liu, Wu Guo, Zhen-Hua Ling
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an algorithm to improve the calculation of confidence measure for spoken term detection (STD). Given an input query term, the algorithm first calculates a measurement named document ranking weight for each document in the speech database to reflect its relevance with the query term by summing all the confidence measures of the hypothesized term occurrences in this document. The confidence measure of each term occurrence is then re-estimated through linear interpolation with the calculated document ranking weight to improve its reliability by integrating document-level information. Experiments are conducted on three standard STD tasks for Tamil, Vietnamese and English respectively. The experimental results all demonstrate that the proposed algorithm achieves consistent improvements over the state-of-the-art method for confidence measure calculation. Furthermore, this algorithm is still effective even if a high accuracy speech recognizer is not available, which makes it applicable for the languages with limited speech resources.

##### Abstract (translated by Google)
本文提出了一种改进语音检测（STD）置信度度量的算法。给定一个输入查询词，算法首先为语音数据库中的每个文档计算一个名为文档排序权重的度量值，以通过将本文档中假设词语出现的所有置信度度量相加来反映其与查询词的相关性。然后通过线性内插重新估计每个词条出现的置信度，并将计算出的文档排序权重通过集成文档级信息来提高其可靠性。泰米尔语，越南语和英语的三个标准STD任务分别进行实验。实验结果都表明，所提出的算法相对于最先进的置信测度计算方法实现了一致的改进。而且，即使没有高精度的语音识别器，该算法仍然是有效的，这使得它适用于语音资源有限的语言。

##### URL
[https://arxiv.org/abs/1509.01899](https://arxiv.org/abs/1509.01899)

##### PDF
[https://arxiv.org/pdf/1509.01899](https://arxiv.org/pdf/1509.01899)

