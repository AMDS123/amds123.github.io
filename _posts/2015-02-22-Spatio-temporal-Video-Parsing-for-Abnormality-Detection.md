---
layout: post
title: "Spatio-temporal Video Parsing for Abnormality Detection"
date: 2015-02-22 14:54:02
categories: arXiv_CV
tags: arXiv_CV Optimization Inference Classification Detection
author: Borislav Antić, Björn Ommer
mathjax: true
---

* content
{:toc}

##### Abstract
Abnormality detection in video poses particular challenges due to the infinite size of the class of all irregular objects and behaviors. Thus no (or by far not enough) abnormal training samples are available and we need to find abnormalities in test data without actually knowing what they are. Nevertheless, the prevailing concept of the field is to directly search for individual abnormal local patches or image regions independent of another. To address this problem, we propose a method for joint detection of abnormalities in videos by spatio-temporal video parsing. The goal of video parsing is to find a set of indispensable normal spatio-temporal object hypotheses that jointly explain all the foreground of a video, while, at the same time, being supported by normal training samples. Consequently, we avoid a direct detection of abnormalities and discover them indirectly as those hypotheses which are needed for covering the foreground without finding an explanation for themselves by normal samples. Abnormalities are localized by MAP inference in a graphical model and we solve it efficiently by formulating it as a convex optimization problem. We experimentally evaluate our approach on several challenging benchmark sets, improving over the state-of-the-art on all standard benchmarks both in terms of abnormality classification and localization.

##### Abstract (translated by Google)
视频中的异常检测由于所有不规则对象和行为的类别的无限大而造成特别的挑战。因此，没有（或者远远不够）的异常训练样本可用，我们需要在测试数据中发现异常而实际上不知道它们是什么。尽管如此，该领域的普遍概念是直接搜索个别异常的局部斑块或独立于另一个的图像区域。为了解决这个问题，我们提出了一种通过时空视频解析来联合检测视频异常的方法。视频解析的目标是找到一组不可或缺的正常时空对象假设，共同解释视频的所有前景，同时受到正常训练样本的支持。因此，我们避免直接检测异常，并间接发现它们作为覆盖前景所需的假设，而不用正常样本找到自己的解释。通过图形模型中的MAP推断来定位异常，并且通过将其表示为凸优化问题来有效地解决异常。我们在几个具有挑战性的基准测试集上实验性地评估了我们的方法，改进了所有标准基准测试中的最新技术，包括异常分类和本地化。

##### URL
[https://arxiv.org/abs/1502.06235](https://arxiv.org/abs/1502.06235)

##### PDF
[https://arxiv.org/pdf/1502.06235](https://arxiv.org/pdf/1502.06235)

