---
layout: post
title: "How to Manipulate CNNs to Make Them Lie: the GradCAM Case"
date: 2019-07-25 08:51:08
categories: arXiv_CV
tags: arXiv_CV
author: Tom Viering, Ziqi Wang, Marco Loog, Elmar Eisemann
mathjax: true
---

* content
{:toc}

##### Abstract
Recently many methods have been introduced to explain CNN decisions. However, it has been shown that some methods can be sensitive to manipulation of the input. We continue this line of work and investigate the explanation method GradCAM. Instead of manipulating the input, we consider an adversary that manipulates the model itself to attack the explanation. By changing weights and architecture, we demonstrate that it is possible to generate any desired explanation, while leaving the model's accuracy essentially unchanged. This illustrates that GradCAM cannot explain the decision of every CNN and provides a proof of concept showing that it is possible to obfuscate the inner workings of a CNN. Finally, we combine input and model manipulation. To this end we put a backdoor in the network: the explanation is correct unless there is a specific pattern present in the input, which triggers a malicious explanation. Our work raises new security concerns, especially in settings where explanations of models may be used to make decisions, such as in the medical domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10901](http://arxiv.org/abs/1907.10901)

##### PDF
[http://arxiv.org/pdf/1907.10901](http://arxiv.org/pdf/1907.10901)

