---
layout: post
title: "Brain2Char: A Deep Architecture for Decoding Text from Brain Recordings"
date: 2019-09-03 18:54:43
categories: arXiv_CL
tags: arXiv_CL Regularization Face Classification Deep_Learning Language_Model
author: Pengfei Sun, Gopala K. Anumanchipalli, Edward F. Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Decoding language representations directly from the brain can enable new Brain-Computer Interfaces (BCI) for high bandwidth human-human and human-machine communication. Clinically, such technologies can restore communication in people with neurological conditions affecting their ability to speak. In this study, we propose a novel deep network architecture Brain2Char, for directly decoding text (specifically character sequences) from direct brain recordings (called Electrocorticography, ECoG). Brain2Char framework combines state-of-the-art deep learning modules --- 3D Inception layers for multiband spatiotemporal feature extraction from neural data and bidirectional recurrent layers, dilated convolution layers followed by language model weighted beam search to decode character sequences, optimizing a connectionist temporal classification (CTC) loss. Additionally, given the highly non-linear transformations that underlie the conversion of cortical function to character sequences, we perform regularizations on the network's latent representations motivated by insights into cortical encoding of speech production and artifactual aspects specific to ECoG data acquisition. To do this, we impose auxiliary losses on latent representations for articulatory movements, speech acoustics and session specific non-linearities. In 3 participants tested here, Brain2Char achieves 10.6\%, 8.5\% and 7.0\% Word Error Rates (WER) respectively on vocabulary sizes ranging from 1200 to 1900 words. Brain2Char also performs well when 2 participants silently mimed sentences. These results set a new state-of-the-art on decoding text from brain and demonstrate the potential of Brain2Char as a high-performance communication BCI.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01401](http://arxiv.org/abs/1909.01401)

##### PDF
[http://arxiv.org/pdf/1909.01401](http://arxiv.org/pdf/1909.01401)

