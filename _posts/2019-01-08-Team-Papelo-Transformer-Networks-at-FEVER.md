---
layout: post
title: "Team Papelo: Transformer Networks at FEVER"
date: 2019-01-08 21:57:30
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Christopher Malon
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a system for the FEVER fact extraction and verification challenge that uses a high precision entailment classifier based on transformer networks pretrained with language modeling, to classify a broad set of potential evidence. The precision of the entailment classifier allows us to enhance recall by considering every statement from several articles to decide upon each claim. We include not only the articles best matching the claim text by TFIDF score, but read additional articles whose titles match named entities and capitalized expressions occurring in the claim text. The entailment module evaluates potential evidence one statement at a time, together with the title of the page the evidence came from (providing a hint about possible pronoun antecedents). In preliminary evaluation, the system achieves .5736 FEVER score, .6108 label accuracy, and .6485 evidence F1 on the FEVER shared task test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02534](http://arxiv.org/abs/1901.02534)

##### PDF
[http://arxiv.org/pdf/1901.02534](http://arxiv.org/pdf/1901.02534)

