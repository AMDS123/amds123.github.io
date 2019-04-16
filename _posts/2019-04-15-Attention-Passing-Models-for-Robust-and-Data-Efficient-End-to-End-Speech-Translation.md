---
layout: post
title: "Attention-Passing Models for Robust and Data-Efficient End-to-End Speech Translation"
date: 2019-04-15 17:33:38
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Matthias Sperber, Graham Neubig, Jan Niehues, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Speech translation has traditionally been approached through cascaded models consisting of a speech recognizer trained on a corpus of transcribed speech, and a machine translation system trained on parallel texts. Several recent works have shown the feasibility of collapsing the cascade into a single, direct model that can be trained in an end-to-end fashion on a corpus of translated speech. However, experiments are inconclusive on whether the cascade or the direct model is stronger, and have only been conducted under the unrealistic assumption that both are trained on equal amounts of data, ignoring other available speech recognition and machine translation corpora. 
 In this paper, we demonstrate that direct speech translation models require more data to perform well than cascaded models, and while they allow including auxiliary data through multi-task training, they are poor at exploiting such data, putting them at a severe disadvantage. As a remedy, we propose the use of end-to-end trainable models with two attention mechanisms, the first establishing source speech to source text alignments, the second modeling source to target text alignment. We show that such models naturally decompose into multi-task-trainable recognition and translation tasks and propose an attention-passing technique that alleviates error propagation issues in a previous formulation of a model with two attention stages. Our proposed model outperforms all examined baselines and is able to exploit auxiliary training data much more effectively than direct attentional models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07209](http://arxiv.org/abs/1904.07209)

##### PDF
[http://arxiv.org/pdf/1904.07209](http://arxiv.org/pdf/1904.07209)

