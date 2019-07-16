---
layout: post
title: "Learn Spelling from Teachers: Transferring Knowledge from Language Models to Sequence-to-Sequence Speech Recognition"
date: 2019-07-13 06:27:24
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Language_Model Recognition
author: Ye Bai, Jiangyan Yi, Jianhua Tao, Zhengkun Tian, Zhengqi Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Integrating an external language model into a sequence-to-sequence speech recognition system is non-trivial. Previous works utilize linear interpolation or a fusion network to integrate external language models. However, these approaches introduce external components, and increase decoding computation. In this paper, we instead propose a knowledge distillation based training approach to integrating external language models into a sequence-to-sequence model. A recurrent neural network language model, which is trained on large scale external text, generates soft labels to guide the sequence-to-sequence model training. Thus, the language model plays the role of the teacher. This approach does not add any external component to the sequence-to-sequence model during testing. And this approach is flexible to be combined with shallow fusion technique together for decoding. The experiments are conducted on public Chinese datasets AISHELL-1 and CLMAD. Our approach achieves a character error rate of 9.3%, which is relatively reduced by 18.42% compared with the vanilla sequence-to-sequence model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06017](http://arxiv.org/abs/1907.06017)

##### PDF
[http://arxiv.org/pdf/1907.06017](http://arxiv.org/pdf/1907.06017)

