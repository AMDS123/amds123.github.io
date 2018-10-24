---
layout: post
title: "Improving Automated Latent Fingerprint Identification using Extended Minutia Types"
date: 2018-10-23 12:02:22
categories: arXiv_CV
tags: arXiv_CV
author: Ram P. Krish, Julian Fierrez, Daniel Ramos, Fernando Alonso-Fernandez, Josef Bigun
mathjax: true
---

* content
{:toc}

##### Abstract
Latent fingerprints are usually processed with Automated Fingerprint Identification Systems (AFIS) by law enforcement agencies to narrow down possible suspects from a criminal database. AFIS do not commonly use all discriminatory features available in fingerprints but typically use only some types of features automatically extracted by a feature extraction algorithm. In this work, we explore ways to improve rank identification accuracies of AFIS when only a partial latent fingerprint is available. Towards solving this challenge, we propose a method that exploits extended fingerprint features (unusual/rare minutiae) not commonly considered in AFIS. This new method can be combined with any existing minutiae-based matcher. We first compute a similarity score based on least squares between latent and tenprint minutiae points, with rare minutiae features as reference points. Then the similarity score of the reference minutiae-based matcher at hand is modified based on a fitting error from the least square similarity stage. We use a realistic forensic fingerprint casework database in our experiments which contains rare minutiae features obtained from Guardia Civil, the Spanish law enforcement agency. Experiments are conducted using three minutiae-based matchers as a reference, namely: NIST-Bozorth3, VeriFinger-SDK and MCC-SDK. We report significant improvements in the rank identification accuracies when these minutiae matchers are augmented with our proposed algorithm based on rare minutiae features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09801](http://arxiv.org/abs/1810.09801)

##### PDF
[http://arxiv.org/pdf/1810.09801](http://arxiv.org/pdf/1810.09801)

