---
layout: post
title: "Are We Safe Yet? The Limitations of Distributional Features for Fake News Detection"
date: 2019-08-26 17:23:22
categories: arXiv_CL
tags: arXiv_CL Object_Detection Attention Language_Model Detection
author: Tal Schuster, Roei Schuster, Darsh J Shah, Regina Barzilay
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic detection of fake news --- texts that are deceitful and misleading --- is a long outstanding and largely unsolved problem. Worse yet, recent developments in language modeling allow for the automatic generation of such texts. One approach that has recently gained attention detects these fake news using stylometry-based provenance, i.e. tracing a text's writing style back to its producing source and determining whether the source is malicious. This was shown to be highly effective under the assumption that legitimate text is produced by humans, and fake text is produced by a language model. 
 In this work, we identify a fundamental problem with provenance-based approaches against attackers that auto-generate fake news: fake and legitimate texts can originate from nearly identical sources. First, a legitimate text might be auto-generated in a similar process to that of fake text, and second, attackers can automatically corrupt articles originating from legitimate human sources. We demonstrate these issues by simulating attacks in such settings, and find that the provenance approach fails to defend against them. Our findings highlight the importance of assessing the veracity of the text rather than solely relying on its style or source. We also open up a discussion on the types of benchmarks that should be used to evaluate neural fake news detectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09805](http://arxiv.org/abs/1908.09805)

##### PDF
[http://arxiv.org/pdf/1908.09805](http://arxiv.org/pdf/1908.09805)

