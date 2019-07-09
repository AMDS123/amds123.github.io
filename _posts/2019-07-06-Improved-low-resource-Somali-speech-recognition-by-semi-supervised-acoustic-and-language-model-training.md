---
layout: post
title: "Improved low-resource Somali speech recognition by semi-supervised acoustic and language model training"
date: 2019-07-06 02:53:10
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Astik Biswas, Raghav Menon, Ewald van der Westhuizen, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
We present improvements in automatic speech recognition (ASR) for Somali, a currently extremely under-resourced language. This forms part of a continuing United Nations (UN) effort to employ ASR-based keyword spotting systems to support humanitarian relief programmes in rural Africa. Using just 1.57 hours of annotated speech data as a seed corpus, we increase the pool of training data by applying semi-supervised training to 17.55 hours of untranscribed speech. We make use of factorised time-delay neural networks (TDNN-F) for acoustic modelling, since these have recently been shown to be effective in resource-scarce situations. Three semi-supervised training passes were performed, where the decoded output from each pass was used for acoustic model training in the subsequent pass. The automatic transcriptions from the best performing pass were used for language model augmentation. To ensure the quality of automatic transcriptions, decoder confidence is used as a threshold. The acoustic and language models obtained from the semi-supervised approach show significant improvement in terms of WER and perplexity compared to the baseline. Incorporating the automatically generated transcriptions yields a 6.55\% improvement in language model perplexity. The use of 17.55 hour of Somali acoustic data in semi-supervised training shows an improvement of 7.74\% relative over the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03064](http://arxiv.org/abs/1907.03064)

##### PDF
[http://arxiv.org/pdf/1907.03064](http://arxiv.org/pdf/1907.03064)

