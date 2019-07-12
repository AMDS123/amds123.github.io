---
layout: post
title: "Polyphonic Sound Event and Sound Activity Detection: A Multi-task approach"
date: 2019-07-11 11:41:44
categories: arXiv_SD
tags: arXiv_SD Prediction Detection
author: Arjun Pankajakshan, Helen L. Bear, Emmanouil Benetos
mathjax: true
---

* content
{:toc}

##### Abstract
Polyphonic Sound Event Detection (SED) in real-world recordings is a challenging task because of the dynamic polyphony level, intensity, and duration of sound events. Current polyphonic SED systems fail to model the temporal structure of sound events explicitly and instead attempt to look at which sound events are present at each audio frame. Consequently, the event-wise detection performance is much lower than the segment-wise detection performance. In this work, we propose a joint model approach to improve the temporal localization of sound events using a multi-task learning setup. The first task predicts which sound events are present at each time frame; we call this branch 'Sound Event Detection (SED) model', while the second task predicts if a sound event is present or not at each frame; we call this branch 'Sound Activity Detection (SAD) model'. We verify the proposed joint model by comparing it with a separate implementation of both tasks aggregated together from individual task predictions. Our experiments on the URBAN-SED dataset show that the proposed joint model can alleviate False Positive (FP) and False Negative (FN) errors and improve both the segment-wise and the event-wise metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05122](http://arxiv.org/abs/1907.05122)

##### PDF
[http://arxiv.org/pdf/1907.05122](http://arxiv.org/pdf/1907.05122)

