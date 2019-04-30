---
layout: post
title: "Missing MRI Pulse Sequence Synthesis using Multi-Modal Generative Adversarial Network"
date: 2019-04-27 20:15:15
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Anmol Sharma, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic resonance imaging (MRI) is being increasingly utilized to assess, diagnose, and plan treatment for a variety of diseases. The ability to visualize tissue in varied contrasts in the form of MR pulse sequences in a single scan provides valuable insights to physicians, as well as enabling automated systems performing downstream analysis. However many issues like prohibitive scan time, image corruption, different acquisition protocols, or allergies to certain contrast materials may hinder the process of acquiring multiple sequences for a patient. This poses challenges to both physicians and automated systems since complementary information provided by the missing sequences is lost. In this paper, we propose a variant of generative adversarial network (GAN) capable of leveraging redundant information contained within multiple available sequences in order to generate one or more missing sequences for a patient scan. The proposed network is designed as a multi-input, multi-output network which combines information from all the available pulse sequences, implicitly infers which sequences are missing, and synthesizes the missing ones in a single forward pass. We demonstrate and validate our method on two brain MRI datasets each with four sequences, and show the applicability of the proposed method in simultaneously synthesizing all missing sequences in any possible scenario where either one, two, or three of the four sequences may be missing. We compare our approach with competing unimodal and multi-modal methods, and show that we outperform both quantitatively and qualitatively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12200](http://arxiv.org/abs/1904.12200)

##### PDF
[http://arxiv.org/pdf/1904.12200](http://arxiv.org/pdf/1904.12200)

