---
layout: post
title: "On the Capabilities and Limitations of Reasoning for Natural Language Understanding"
date: 2019-01-08 21:19:34
categories: arXiv_AI
tags: arXiv_AI
author: Daniel Khashabi, Erfan Sadeqi Azer, Tushar Khot, Ashish Sabharwal, Dan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Recent systems for natural language understanding are strong at overcoming linguistic variability for lookup style reasoning. Yet, their accuracy drops dramatically as the number of reasoning steps increases. We present the first formal framework to study such empirical observations, addressing the ambiguity, redundancy, incompleteness, and inaccuracy that the use of language introduces when representing a hidden conceptual space. Our formal model uses two interrelated spaces: a conceptual meaning space that is unambiguous and complete but hidden, and a linguistic symbol space that captures a noisy grounding of the meaning space in the symbols or words of a language. 
 We apply this framework to study the connectivity problem in undirected graphs---a core reasoning problem that forms the basis for more complex multi-hop reasoning. We show that it is indeed possible to construct a high-quality algorithm for detecting connectivity in the (latent) meaning graph, based on an observed noisy symbol graph, as long as the noise is below our quantified noise level and only a few hops are needed. On the other hand, we also prove an impossibility result: if a query requires a large number (specifically, logarithmic in the size of the meaning graph) of hops, no reasoning system operating over the symbol graph is likely to recover any useful property of the meaning graph. This highlights a fundamental barrier for a class of reasoning problems and systems, and suggests the need to limit the distance between the two spaces, rather than investing in multi-hop reasoning with "many" hops.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02522](http://arxiv.org/abs/1901.02522)

##### PDF
[http://arxiv.org/pdf/1901.02522](http://arxiv.org/pdf/1901.02522)

