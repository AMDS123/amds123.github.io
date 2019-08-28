---
layout: post
title: "Datalog Reasoning over Compressed RDF Knowledge Bases"
date: 2019-08-27 13:12:21
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Pan Hu, Jacopo Urbani, Boris Motik, Ian Horrocks
mathjax: true
---

* content
{:toc}

##### Abstract
Materialisation is often used in RDF systems to derive, in a preprocessing step, all facts implied by given RDF triples and rules. Although widely used, materialisation considers all possible rule applications and can use a lot of memory for storing the derived facts, which can hinder performance. We present a novel materialisation technique that compresses the RDF triples so that the rules can sometimes be applied to multiple facts at once, and the derived facts can be represented using structure sharing. Our technique can thus require less space, as well as skip certain rule applications. Our experiments show that our technique can be very effective: when the rules are relatively simple, our system is both faster and requires less memory than prominent state-of-the-art systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10177](http://arxiv.org/abs/1908.10177)

##### PDF
[http://arxiv.org/pdf/1908.10177](http://arxiv.org/pdf/1908.10177)

