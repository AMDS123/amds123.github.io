---
layout: post
title: "Multi-Source Neural Machine Translation with Missing Data"
date: 2018-06-08 01:29:32
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yuta Nishimura, Katsuhito Sudoh, Graham Neubig, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-source translation is an approach to exploit multiple inputs (e.g. in two different languages) to increase translation accuracy. In this paper, we examine approaches for multi-source neural machine translation (NMT) using an incomplete multilingual corpus in which some translations are missing. In practice, many multilingual corpora are not complete due to the difficulty to provide translations in all of the relevant languages (for example, in TED talks, most English talks only have subtitles for a small portion of the languages that TED supports). Existing studies on multi-source translation did not explicitly handle such situations. This study focuses on the use of incomplete multilingual corpora in multi-encoder NMT and mixture of NMT experts and examines a very simple implementation where missing source translations are replaced by a special symbol <NULL>. These methods allow us to use incomplete corpora both at training time and test time. In experiments with real incomplete multilingual corpora of TED Talks, the multi-source NMT with the <NULL> tokens achieved higher translation accuracies measured by BLEU than those by any one-to-one NMT systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.02525](https://arxiv.org/abs/1806.02525)

##### PDF
[https://arxiv.org/pdf/1806.02525](https://arxiv.org/pdf/1806.02525)

