---
layout: post
title: "The MeMAD Submission to the IWSLT 2018 Speech Translation Task"
date: 2018-10-24 12:18:44
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition NMT Recognition
author: Umut Sulubacak, Jörg Tiedemann, Aku Rouhe, Stig-Arne Grönroos, Mikko Kurimo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes the MeMAD project entry to the IWSLT Speech Translation Shared Task, addressing the translation of English audio into German text. Between the pipeline and end-to-end model tracks, we participated only in the former, with three contrastive systems. We tried also the latter, but were not able to finish our end-to-end model in time. All of our systems start by transcribing the audio into text through an automatic speech recognition (ASR) model trained on the TED-LIUM English Speech Recognition Corpus (TED-LIUM). Afterwards, we feed the transcripts into English-German text-based neural machine translation (NMT) models. Our systems employ three different translation models trained on separate training sets compiled from the English-German part of the TED Speech Translation Corpus (TED-Trans) and the OpenSubtitles2018 section of the OPUS collection. In this paper, we also describe the experiments leading up to our final systems. Our experiments indicate that using OpenSubtitles2018 in training significantly improves translation performance. We also experimented with various pre- and postprocessing routines for the NMT module, but we did not have much success with these. Our best-scoring system attains a BLEU score of 16.45 on the test set for this year's task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10320](https://arxiv.org/abs/1810.10320)

##### PDF
[https://arxiv.org/pdf/1810.10320](https://arxiv.org/pdf/1810.10320)

