---
layout: post
title: "Joint Speech Recognition and Speaker Diarization via Sequence Transduction"
date: 2019-07-09 00:23:22
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Laurent El Shafey, Hagen Soltau, Izhak Shafran
mathjax: true
---

* content
{:toc}

##### Abstract
Speech applications dealing with conversations require not only recognizing the spoken words, but also determining who spoke when. The task of assigning words to speakers is typically addressed by merging the outputs of two separate systems, namely, an automatic speech recognition (ASR) system and a speaker diarization (SD) system. The two systems are trained independently with different objective functions. Often the SD systems operate directly on the acoustics and are not constrained to respect word boundaries and this deficiency is overcome in an ad hoc manner. Motivated by recent advances in sequence to sequence learning, we propose a novel approach to tackle the two tasks by a joint ASR and SD system using a recurrent neural network transducer. Our approach utilizes both linguistic and acoustic cues to infer speaker roles, as opposed to typical SD systems, which only use acoustic cues. We evaluated the performance of our approach on a large corpus of medical conversations between physicians and patients. Compared to a competitive conventional baseline, our approach improves word-level diarization error rate from 15.8% to 2.2%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05337](http://arxiv.org/abs/1907.05337)

##### PDF
[http://arxiv.org/pdf/1907.05337](http://arxiv.org/pdf/1907.05337)

