---
layout: post
title: "Towards usable automated detection of CPU architecture and endianness for arbitrary binary files and object code sequences"
date: 2019-08-15 08:49:06
categories: arXiv_CV
tags: arXiv_CV Detection
author: Sami Kairajärvi, Andrei Costin, Timo Hämäläinen
mathjax: true
---

* content
{:toc}

##### Abstract
Static and dynamic binary analysis techniques are actively used to reverse engineer software's behavior and to detect its vulnerabilities, even when only the binary code is available for analysis. To avoid analysis errors due to misreading op-codes for a wrong CPU architecture, these analysis tools must precisely identify the Instruction Set Architecture (ISA) of the object code under analysis. The variety of CPU architectures that modern security and reverse engineering tools must support is ever increasing due to massive proliferation of IoT devices and the diversity of firmware and malware targeting those devices. Recent studies concluded that falsely identifying the binary code's ISA caused alone about 10\% of failures of IoT firmware analysis. The state of the art approaches to detect ISA for arbitrary object code look promising - their results demonstrate effectiveness and high-performance. However, they lack the support of publicly available datasets and toolsets, which makes the evaluation, comparison, and improvement of those techniques, datasets, and machine learning models quite challenging (if not impossible). This paper bridges multiple gaps in the field of automated and precise identification of architecture and endianness of binary files and object code. We develop from scratch the toolset and datasets that are lacking in this research space. As such, we contribute a comprehensive collection of open data, open source, and open API web-services. We also attempt experiment reconstruction and cross-validation of effectiveness, efficiency, and results of the state of the art methods. When training and testing classifiers using solely code-sections from executable binary files, all our classifiers performed equally well achieving over 98\% accuracy. The results are consistent and comparable with the current state of the art, hence supports the general validity of the algorithms

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05459](https://arxiv.org/abs/1908.05459)

##### PDF
[https://arxiv.org/pdf/1908.05459](https://arxiv.org/pdf/1908.05459)

