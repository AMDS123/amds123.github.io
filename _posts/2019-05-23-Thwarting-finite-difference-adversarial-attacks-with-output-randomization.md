---
layout: post
title: "Thwarting finite difference adversarial attacks with output randomization"
date: 2019-05-23 18:58:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Haidar Khan, Daniel Park, Azer Khan, B&#xfc;lent Yener
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples pose a threat to deep neural network models in a variety of scenarios, from settings where the adversary has complete knowledge of the model and to the opposite "black box" setting. Black box attacks are particularly threatening as the adversary only needs access to the input and output of the model. Defending against black box adversarial example generation attacks is paramount as currently proposed defenses are not effective. Since these types of attacks rely on repeated queries to the model to estimate gradients over input dimensions, we investigate the use of randomization to thwart such adversaries from successfully creating adversarial examples. Randomization applied to the output of the deep neural network model has the potential to confuse potential attackers, however this introduces a tradeoff between accuracy and robustness. We show that for certain types of randomization, we can bound the probability of introducing errors by carefully setting distributional parameters. For the particular case of finite difference black box attacks, we quantify the error introduced by the defense in the finite difference estimate of the gradient. Lastly, we show empirically that the defense can thwart two adaptive black box adversarial attack algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09871](http://arxiv.org/abs/1905.09871)

##### PDF
[http://arxiv.org/pdf/1905.09871](http://arxiv.org/pdf/1905.09871)

