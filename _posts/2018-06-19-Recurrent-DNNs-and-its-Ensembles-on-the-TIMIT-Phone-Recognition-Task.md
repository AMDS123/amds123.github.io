---
layout: post
title: "Recurrent DNNs and its Ensembles on the TIMIT Phone Recognition Task"
date: 2018-06-19 12:39:22
categories: arXiv_CL
tags: arXiv_CL Regularization Knowledge Speech_Recognition Recognition
author: Jan Vanek, Josef Michalek, Josef Psutka
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we have investigated recurrent deep neural networks (DNNs) in combination with regularization techniques as dropout, zoneout, and regularization post-layer. As a benchmark, we chose the TIMIT phone recognition task due to its popularity and broad availability in the community. It also simulates a low-resource scenario that is helpful in minor languages. Also, we prefer the phone recognition task because it is much more sensitive to an acoustic model quality than a large vocabulary continuous speech recognition task. In recent years, recurrent DNNs pushed the error rates in automatic speech recognition down. But, there was no clear winner in proposed architectures. The dropout was used as the regularization technique in most cases, but combination with other regularization techniques together with model ensembles was omitted. However, just an ensemble of recurrent DNNs performed best and achieved an average phone error rate from 10 experiments 14.84 % (minimum 14.69 %) on core test set that is slightly lower then the best-published PER to date, according to our knowledge. Finally, in contrast of the most papers, we published the open-source scripts to easily replicate the results and to help continue the development.

##### Abstract (translated by Google)
在本文中，我们研究了经常性深度神经网络（DNN）与正则化技术相结合作为退出，区域输出和正则化后层。作为一个基准，我们选择了TIMIT手机识别任务，因为它在社区中的流行度和广泛的可用性。它还模拟了对小语言有用的低资源情况。此外，我们更喜欢手机识别任务，因为它比声音模型质量更敏感，而不是大量的词汇连续语音识别任务。近年来，经常性的DNN将自动语音识别中的错误率降低了。但是，在提出的架构中并没有明显的赢家。在大多数情况下，失落被用作正则化技术，但是与其他正则化技术一起与模型合奏被省略。然而，根据我们的知识，只有经常性DNN的集合表现最好，并且在核心测试集中的10次实验中的平均电话错误率为14.84％（最低14.69％），略低于迄今为止公布的最佳PER。最后，与大多数论文相比，我们发布了开源脚本以轻松复制结果并帮助继续开发。

##### URL
[http://arxiv.org/abs/1806.07186](http://arxiv.org/abs/1806.07186)

##### PDF
[http://arxiv.org/pdf/1806.07186](http://arxiv.org/pdf/1806.07186)

