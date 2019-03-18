---
layout: post
title: "On Evaluation of Adversarial Perturbations for Sequence-to-Sequence Models"
date: 2019-03-15 16:04:11
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Paul Michel, Xian Li, Graham Neubig, Juan Miguel Pino
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples --- perturbations to the input of a model that elicit large changes in the output --- have been shown to be an effective way of assessing the robustness of sequence-to-sequence (seq2seq) models. However, these perturbations only indicate weaknesses in the model if they do not change the input so significantly that it legitimately results in changes in the expected output. This fact has largely been ignored in the evaluations of the growing body of related literature. Using the example of untargeted attacks on machine translation (MT), we propose a new evaluation framework for adversarial attacks on seq2seq models that takes the semantic equivalence of the pre- and post-perturbation input into account. Using this framework, we demonstrate that existing methods may not preserve meaning in general, breaking the aforementioned assumption that source side perturbations should not result in changes in the expected output. We further use this framework to demonstrate that adding additional constraints on attacks allows for adversarial perturbations that are more meaning-preserving, but nonetheless largely change the output sequence. Finally, we show that performing untargeted adversarial training with meaning-preserving attacks is beneficial to the model in terms of adversarial robustness, without hurting test performance. A toolkit implementing our evaluation framework is released at https://github.com/pmichel31415/teapot-nlp.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06620](http://arxiv.org/abs/1903.06620)

##### PDF
[http://arxiv.org/pdf/1903.06620](http://arxiv.org/pdf/1903.06620)

