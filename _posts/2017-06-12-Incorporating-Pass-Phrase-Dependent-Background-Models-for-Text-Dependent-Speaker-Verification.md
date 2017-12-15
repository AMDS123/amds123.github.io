---
layout: post
title: "Incorporating Pass-Phrase Dependent Background Models for Text-Dependent Speaker Verification"
date: 2017-06-12 16:42:56
categories: arXiv_CL
tags: arXiv_CL
author: A. K. Sarkar, Zheng-Hua Tan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose pass-phrase dependent background models (PBMs) for text-dependent (TD) speaker verification (SV) to integrate the pass-phrase identification process into the conventional TD-SV system, where a PBM is derived from a text-independent background model through adaptation using the utterances of a particular pass-phrase. During training, pass-phrase specific target speaker models are derived from the particular PBM using the training data for the respective target model. While testing, the best PBM is first selected for the test utterance in the maximum likelihood (ML) sense and the selected PBM is then used for the log likelihood ratio (LLR) calculation with respect to the claimant model. The proposed method incorporates the pass-phrase identification step in the LLR calculation, which is not considered in conventional standalone TD-SV systems. The performance of the proposed method is compared to conventional text-independent background model based TD-SV systems using either Gaussian mixture model (GMM)-universal background model (UBM) or Hidden Markov model (HMM)-UBM or i-vector paradigms. In addition, we consider two approaches to build PBMs: speaker-independent and speaker-dependent. We show that the proposed method significantly reduces the error rates of text-dependent speaker verification for the non-target types: target-wrong and imposter-wrong while it maintains comparable TD-SV performance when imposters speak a correct utterance with respect to the conventional system. Experiments are conducted on the RedDots challenge and the RSR2015 databases that consist of short utterances.

##### Abstract (translated by Google)
在本文中，我们提出了用于文本相关（TD）讲话者验证（SV）的口令相关背景模型（PBM），以将口令识别过程集成到常规TD-SV系统中，其中PBM是从独立于文本的背景模型通过使用特定通行短语的发音进行适应。在训练期间，使用针对相应目标模型的训练数据从特定的PBM导出通行短语特定目标讲话者模型。在测试时，首先选择最好的PBM用于最大似然（ML）意义上的测试话语，然后将所选的PBM用于关于申请人模型的对数似然比（LLR）计算。所提出的方法在LLR计算中结合了口令识别步骤，这在传统的独立TD-SV系统中没有考虑。所提出的方法的性能与使用高斯混合模型（GMM） - 通用背景模型（UBM）或隐马尔科夫模型（HMM）-UBM或i-矢量范例的基于文本独立背景模型的TD-SV系统进行比较。另外，我们考虑两种建立PBM的方法：独立于说话者和说话者。我们表明，提出的方法显着降低了非目标类型的文本相关说话人验证的错误率：目标错误和冒名顶替错误，同时保持可比的TD-SV性能，当冒名顶替者就正常的话语系统。在RedDots挑战赛和由短话组成的RSR2015数据库上进行实验。

##### URL
[https://arxiv.org/abs/1611.06423](https://arxiv.org/abs/1611.06423)

##### PDF
[https://arxiv.org/pdf/1611.06423](https://arxiv.org/pdf/1611.06423)

