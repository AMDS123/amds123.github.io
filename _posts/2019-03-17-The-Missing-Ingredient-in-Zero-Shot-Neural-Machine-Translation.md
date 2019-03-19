---
layout: post
title: "The Missing Ingredient in Zero-Shot Neural Machine Translation"
date: 2019-03-17 14:01:53
categories: arXiv_AI
tags: arXiv_AI NMT
author: Naveen Arivazhagan, Ankur Bapna, Orhan Firat, Roee Aharoni, Melvin Johnson, Wolfgang Macherey
mathjax: true
---

* content
{:toc}

##### Abstract
Multilingual Neural Machine Translation (NMT) models are capable of translating between multiple source and target languages. Despite various approaches to train such models, they have difficulty with zero-shot translation: translating between language pairs that were not together seen during training. In this paper we first diagnose why state-of-the-art multilingual NMT models that rely purely on parameter sharing, fail to generalize to unseen language pairs. We then propose auxiliary losses on the NMT encoder that impose representational invariance across languages. Our simple approach vastly improves zero-shot translation quality without regressing on supervised directions. For the first time, on WMT14 English-FrenchGerman, we achieve zero-shot performance that is on par with pivoting. We also demonstrate the easy scalability of our approach to multiple languages on the IWSLT 2017 shared task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07091](http://arxiv.org/abs/1903.07091)

##### PDF
[http://arxiv.org/pdf/1903.07091](http://arxiv.org/pdf/1903.07091)

