---
layout: post
title: "A hypothesize-and-verify framework for Text Recognition using Deep Recurrent Neural Networks"
date: 2015-02-26 13:18:09
categories: arXiv_CV
tags: arXiv_CV Segmentation RNN Language_Model Recognition
author: Anupama Ray, Sai Rajeswar, Santanu Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
Deep LSTM is an ideal candidate for text recognition. However text recognition involves some initial image processing steps like segmentation of lines and words which can induce error to the recognition system. Without segmentation, learning very long range context is difficult and becomes computationally intractable. Therefore, alternative soft decisions are needed at the pre-processing level. This paper proposes a hybrid text recognizer using a deep recurrent neural network with multiple layers of abstraction and long range context along with a language model to verify the performance of the deep neural network. In this paper we construct a multi-hypotheses tree architecture with candidate segments of line sequences from different segmentation algorithms at its different branches. The deep neural network is trained on perfectly segmented data and tests each of the candidate segments, generating unicode sequences. In the verification step, these unicode sequences are validated using a sub-string match with the language model and best first search is used to find the best possible combination of alternative hypothesis from the tree structure. Thus the verification framework using language models eliminates wrong segmentation outputs and filters recognition errors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.07540](https://arxiv.org/abs/1502.07540)

##### PDF
[https://arxiv.org/pdf/1502.07540](https://arxiv.org/pdf/1502.07540)

