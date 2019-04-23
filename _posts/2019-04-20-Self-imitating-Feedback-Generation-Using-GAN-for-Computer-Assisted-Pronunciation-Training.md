---
layout: post
title: "Self-imitating Feedback Generation Using GAN for Computer-Assisted Pronunciation Training"
date: 2019-04-20 06:21:52
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN
author: Seung Hee Yang, Minhwa Chung
mathjax: true
---

* content
{:toc}

##### Abstract
Self-imitating feedback is an effective and learner-friendly method for non-native learners in Computer-Assisted Pronunciation Training. Acoustic characteristics in native utterances are extracted and transplanted onto learner's own speech input, and given back to the learner as a corrective feedback. Previous works focused on speech conversion using prosodic transplantation techniques based on PSOLA algorithm. Motivated by the visual differences found in spectrograms of native and non-native speeches, we investigated applying GAN to generate self-imitating feedback by utilizing generator's ability through adversarial training. Because this mapping is highly under-constrained, we also adopt cycle consistency loss to encourage the output to preserve the global structure, which is shared by native and non-native utterances. Trained on 97,200 spectrogram images of short utterances produced by native and non-native speakers of Korean, the generator is able to successfully transform the non-native spectrogram input to a spectrogram with properties of self-imitating feedback. Furthermore, the transformed spectrogram shows segmental corrections that cannot be obtained by prosodic transplantation. Perceptual test comparing the self-imitating and correcting abilities of our method with the baseline PSOLA method shows that the generative approach with cycle consistency loss is promising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09407](http://arxiv.org/abs/1904.09407)

##### PDF
[http://arxiv.org/pdf/1904.09407](http://arxiv.org/pdf/1904.09407)

