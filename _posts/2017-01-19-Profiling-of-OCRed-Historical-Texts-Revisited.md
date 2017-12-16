---
layout: post
title: "Profiling of OCR'ed Historical Texts Revisited"
date: 2017-01-19 11:31:14
categories: arXiv_CV
tags: arXiv_CV OCR Detection Recognition
author: Florian Fink, Klaus-U. Schulz, Uwe Springmann
mathjax: true
---

* content
{:toc}

##### Abstract
In the absence of ground truth it is not possible to automatically determine the exact spectrum and occurrences of OCR errors in an OCR'ed text. Yet, for interactive postcorrection of OCR'ed historical printings it is extremely useful to have a statistical profile available that provides an estimate of error classes with associated frequencies, and that points to conjectured errors and suspicious tokens. The method introduced in Reffle (2013) computes such a profile, combining lexica, pattern sets and advanced matching techniques in a specialized Expectation Maximization (EM) procedure. Here we improve this method in three respects: First, the method in Reffle (2013) is not adaptive: user feedback obtained by actual postcorrection steps cannot be used to compute refined profiles. We introduce a variant of the method that is open for adaptivity, taking correction steps of the user into account. This leads to higher precision with respect to recognition of erroneous OCR tokens. Second, during postcorrection often new historical patterns are found. We show that adding new historical patterns to the linguistic background resources leads to a second kind of improvement, enabling even higher precision by telling historical spellings apart from OCR errors. Third, the method in Reffle (2013) does not make any active use of tokens that cannot be interpreted in the underlying channel model. We show that adding these uninterpretable tokens to the set of conjectured errors leads to a significant improvement of the recall for error detection, at the same time improving precision.

##### Abstract (translated by Google)
在缺乏基础事实的情况下，不可能自动确定OCR文本中OCR错误的确切频谱和发生情况。然而，对于OCR的历史印刷的交互式后校正，具有可用的统计简档是非常有用的，该统计简档提供了具有相关频率的误差类别的估计，并且指出了猜测错误和可疑的标记。在Reffle（2013）中引入的方法计算了一个这样的概况，在一个专门的期望最大化（EM）过程中结合了词法，模式集和高级匹配技术。这里我们在三个方面改进这个方法：首先，Reffle（2013）中的方法不是自适应的：通过实际的后校正步骤获得的用户反馈不能用来计算精化的轮廓。我们引入了一个开放的适应性方法的变体，考虑用户的纠正步骤。这导致了对于错误的OCR令牌的识别的更高精度。其次，在后矫正过程中，往往会找到新的历史模式。我们表明，将新的历史模式添加到语言背景资源导致了第二种改进，通过告诉历史拼写除了OCR错误以外，还可以实现更高的精度。第三，Reffle（2013）中的方法没有积极使用不能在底层通道模型中解释的令牌。我们表明，将这些不可解释的标记添加到猜测错误的集合导致错误检测召回的显着改善，同时提高了精度。

##### URL
[https://arxiv.org/abs/1701.05377](https://arxiv.org/abs/1701.05377)

##### PDF
[https://arxiv.org/pdf/1701.05377](https://arxiv.org/pdf/1701.05377)

