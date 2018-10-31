---
layout: post
title: "Informed Democracy: Voting-based Novelty Detection for Action Recognition"
date: 2018-10-30 15:42:55
categories: arXiv_CV
tags: arXiv_CV OCR Action_Recognition Classification Prediction Detection Recognition
author: Alina Roitberg, Ziad Al-Halah, Rainer Stiefelhagen
mathjax: true
---

* content
{:toc}

##### Abstract
Novelty detection is crucial for real-life applications. While it is common in activity recognition to assume a closed-set setting, i.e. test samples are always of training categories, this assumption is impractical in a real-world scenario. Test samples can be of various categories including those never seen before during training. Thus, being able to know what we know and what we do not know is decisive for the model to avoid what can be catastrophic consequences. We present in this work a novel approach for identifying samples of activity classes that are not previously seen by the classifier. Our model employs a voting-based scheme that leverages the estimated uncertainty of the individual classifiers in their predictions to measure the novelty of a new input sample. Furthermore, the voting is privileged to a subset of informed classifiers that can best estimate whether a sample is novel or not when it is classified to a certain known category. In a thorough evaluation on UCF-101 and HMDB-51, we show that our model consistently outperforms state-of-the-art in novelty detection. Additionally, by combining our model with off-the-shelf zero-shot learning (ZSL) approaches, our model leads to a significant improvement in action classification accuracy for the generalized ZSL setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12819](http://arxiv.org/abs/1810.12819)

##### PDF
[http://arxiv.org/pdf/1810.12819](http://arxiv.org/pdf/1810.12819)

