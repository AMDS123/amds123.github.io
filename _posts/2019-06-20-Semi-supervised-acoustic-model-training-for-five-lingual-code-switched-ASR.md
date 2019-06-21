---
layout: post
title: "Semi-supervised acoustic model training for five-lingual code-switched ASR"
date: 2019-06-20 14:11:55
categories: arXiv_CL
tags: arXiv_CL Sparse Language_Model
author: Astik Biswas, Emre Y&#x131;lmaz, Febe de Wet, Ewald van der Westhuizen, Thomas Niesler
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents recent progress in the acoustic modelling of under-resourced code-switched (CS) speech in multiple South African languages. We consider two approaches. The first constructs separate bilingual acoustic models corresponding to language pairs (English-isiZulu, English-isiXhosa, English-Setswana and English-Sesotho). The second constructs a single unified five-lingual acoustic model representing all the languages (English, isiZulu, isiXhosa, Setswana and Sesotho). For these two approaches we consider the effectiveness of semi-supervised training to increase the size of the very sparse acoustic training sets. Using approximately 11 hours of untranscribed speech, we show that both approaches benefit from semi-supervised training. The bilingual TDNN-F acoustic models also benefit from the addition of CNN layers (CNN-TDNN-F), while the five-lingual system does not show any significant improvement. Furthermore, because English is common to all language pairs in our data, it dominates when training a unified language model, leading to improved English ASR performance at the expense of the other languages. Nevertheless, the five-lingual model offers flexibility because it can process more than two languages simultaneously, and is therefore an attractive option as an automatic transcription system in a semi-supervised training pipeline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08647](http://arxiv.org/abs/1906.08647)

##### PDF
[http://arxiv.org/pdf/1906.08647](http://arxiv.org/pdf/1906.08647)

