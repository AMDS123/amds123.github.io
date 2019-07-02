---
layout: post
title: "Contextual Phonetic Pretraining for End-to-end Utterance-level Language and Speaker Recognition"
date: 2019-06-30 20:54:21
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Inference Recognition
author: Shaoshi Ling, Julian Salazar, Katrin Kirchhoff
mathjax: true
---

* content
{:toc}

##### Abstract
Pretrained contextual word representations in NLP have greatly improved performance on various downstream tasks. For speech, we propose contextual frame representations that capture phonetic information at the acoustic frame level and can be used for utterance-level language, speaker, and speech recognition. These representations come from the frame-wise intermediate representations of an end-to-end, self-attentive ASR model (SAN-CTC) on spoken utterances. We first train the model on the Fisher English corpus with context-independent phoneme labels, then use its representations at inference time as features for task-specific models on the NIST LRE07 closed-set language recognition task and a Fisher speaker recognition task, giving significant improvements over the state-of-the-art on both (e.g., language EER of 4.68% on 3sec utterances, 23% relative reduction in speaker EER). Results remain competitive when using a novel dilated convolutional model for language recognition, or when ASR pretraining is done with character labels only.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00457](http://arxiv.org/abs/1907.00457)

##### PDF
[http://arxiv.org/pdf/1907.00457](http://arxiv.org/pdf/1907.00457)

