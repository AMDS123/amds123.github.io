---
layout: post
title: "Visual Question Answering as a Meta Learning Task"
date: 2017-11-22 02:04:31
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Damien Teney, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
The predominant approach to Visual Question Answering (VQA) demands that the model represents within its weights all of the information required to answer any question about any image. Learning this information from any real training set seems unlikely, and representing it in a reasonable number of weights doubly so. We propose instead to approach VQA as a meta learning task, thus separating the question answering method from the information required. At test time, the method is provided with a support set of example questions/answers, over which it reasons to resolve the given question. The support set is not fixed and can be extended without retraining, thereby expanding the capabilities of the model. To exploit this dynamically provided information, we adapt a state-of-the-art VQA model with two techniques from the recent meta learning literature, namely prototypical networks and meta networks. Experiments demonstrate the capability of the system to learn to produce completely novel answers (i.e. never seen during training) from examples provided at test time. In comparison to the existing state of the art, the proposed method produces qualitatively distinct results with higher recall of rare answers, and a better sample efficiency that allows training with little initial data. More importantly, it represents an important step towards vision-and-language methods that can learn and reason on-the-fly.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.08105](https://arxiv.org/abs/1711.08105)

##### PDF
[https://arxiv.org/pdf/1711.08105](https://arxiv.org/pdf/1711.08105)

