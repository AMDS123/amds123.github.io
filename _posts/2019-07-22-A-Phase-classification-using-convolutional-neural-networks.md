---
layout: post
title: "A-Phase classification using convolutional neural networks"
date: 2019-07-22 13:10:38
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Edgar R. Arce-Santana, Alfonso Alba, Martin O. Mendez, Valdemar Arce-Guevara
mathjax: true
---

* content
{:toc}

##### Abstract
A series of short events, called A-phases, can be observed in the human electroencephalogram during NREM sleep. These events can be classified in three groups (A1, A2 and A3) according to their spectral contents, and are thought to play a role in the transitions between the different sleep stages. A-phase detection and classification is usually performed manually by a trained expert, but it is a tedious and time-consuming task. In the past two decades, various researchers have designed algorithms to automatically detect and classify the A-phases with varying degrees of success, but the problem remains open. In this paper, a different approach is proposed: instead of attempting to design a general classifier for all subjects, we propose to train ad-hoc classifiers for each subject using as little data as possible, in order to drastically reduce the amount of time required from the expert. The proposed classifiers are based on deep convolutional neural networks using the log-spectrogram of the EEG signal as input data. Results are encouraging, achieving average accuracies of 80.31% when discriminating between A-phases and non A-phases, and 71.87% when classifying among A-phase sub-types, with only 25% of the total A-phases used for training. When additional expert-validated data is considered, the sub-type classification accuracy increases to 78.92%. These results show that a semi-automatic annotation system with assistance from an expert could provide a better alternative to fully automatic classifiers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09296](http://arxiv.org/abs/1907.09296)

##### PDF
[http://arxiv.org/pdf/1907.09296](http://arxiv.org/pdf/1907.09296)

