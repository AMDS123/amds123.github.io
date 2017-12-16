---
layout: post
title: "Fast low-level pattern matching algorithm"
date: 2016-11-18 15:05:30
categories: arXiv_CV
tags: arXiv_CV
author: Janja Paliska Soldo, Ana Sovic Krzic, and Damir Sersic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on pattern matching in the DNA sequence. It was inspired by a previously reported method that proposes encoding both pattern and sequence using prime numbers. Although fast, the method is limited to rather small pattern lengths, due to computing precision problem. Our approach successfully deals with large patterns, due to our implementation that uses modular arithmetic. In order to get the results very fast, the code was adapted for multithreading and parallel implementations. The method is reduced to assembly language level instructions, thus the final result shows significant time and memory savings compared to the reference algorithm.

##### Abstract (translated by Google)
本文着重于DNA序列中的模式匹配。它受到之前报道的方法的启发，提出使用素数编码模式和序列。由于计算精度问题，该方法虽然速度很快，但限于相当小的模式长度。由于我们使用模块化算法的实现，我们的方法成功地处理了大型模式。为了得到非常快的结果，代码被改编为多线程和并行实现。该方法被简化为汇编语言级指令，因此与参考算法相比，最终结果显示出显着的时间和内存节省。

##### URL
[https://arxiv.org/abs/1611.06115](https://arxiv.org/abs/1611.06115)

##### PDF
[https://arxiv.org/pdf/1611.06115](https://arxiv.org/pdf/1611.06115)

