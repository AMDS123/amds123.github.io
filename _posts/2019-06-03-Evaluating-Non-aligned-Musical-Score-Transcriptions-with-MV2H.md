---
layout: post
title: "Evaluating Non-aligned Musical Score Transcriptions with MV2H"
date: 2019-06-03 04:30:04
categories: arXiv_SD
tags: arXiv_SD
author: Andrew McLeod
mathjax: true
---

* content
{:toc}

##### Abstract
The original MV2H metric was designed to evaluate systems which transcribe from an input audio (or MIDI) piece to a complete musical score. However, it requires both the transcribed score and the ground truth score to be time-aligned with the input. Some recent work has begun to transcribe directly from an audio signal into a musical score, skipping the alignment step. This paper introduces an automatic alignment method based on dynamic time warp which allows for MV2H to be used to evaluate such non-aligned transcriptions. This has the additional benefit of allowing non-aligned musical scores---which are significantly more widely available than aligned ones---to be used as ground truth. The code for the improved MV2H, which now also includes a MusicXML parser, and allows for key and time signature changes, is available at www.github.com/apmcleod/MV2H.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00566](http://arxiv.org/abs/1906.00566)

##### PDF
[http://arxiv.org/pdf/1906.00566](http://arxiv.org/pdf/1906.00566)

