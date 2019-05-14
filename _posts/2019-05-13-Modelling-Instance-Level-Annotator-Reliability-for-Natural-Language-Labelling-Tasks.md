---
layout: post
title: "Modelling Instance-Level Annotator Reliability for Natural Language Labelling Tasks"
date: 2019-05-13 11:40:09
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification
author: Maolin Li, Arvid Fahlstr&#xf6;m Myrman, Tingting Mu, Sophia Ananiadou
mathjax: true
---

* content
{:toc}

##### Abstract
When constructing models that learn from noisy labels produced by multiple annotators, it is important to accurately estimate the reliability of annotators. Annotators may provide labels of inconsistent quality due to their varying expertise and reliability in a domain. Previous studies have mostly focused on estimating each annotator's overall reliability on the entire annotation task. However, in practice, the reliability of an annotator may depend on each specific instance. Only a limited number of studies have investigated modelling per-instance reliability and these only considered binary labels. In this paper, we propose an unsupervised model which can handle both binary and multi-class labels. It can automatically estimate the per-instance reliability of each annotator and the correct label for each instance. We specify our model as a probabilistic model which incorporates neural networks to model the dependency between latent variables and instances. For evaluation, the proposed method is applied to both synthetic and real data, including two labelling tasks: text classification and textual entailment. Experimental results demonstrate our novel method can not only accurately estimate the reliability of annotators across different instances, but also achieve superior performance in predicting the correct labels and detecting the least reliable annotators compared to state-of-the-art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04981](http://arxiv.org/abs/1905.04981)

##### PDF
[http://arxiv.org/pdf/1905.04981](http://arxiv.org/pdf/1905.04981)

