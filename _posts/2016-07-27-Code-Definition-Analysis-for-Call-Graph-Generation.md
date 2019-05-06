---
layout: post
title: "Code Definition Analysis for Call Graph Generation"
date: 2016-07-27 03:05:37
categories: arXiv_CV
tags: arXiv_CV Face
author: Anne Veenendaal, Elliot Daly, Eddie Jones, Zhao Gang, Sumalini Vartak, Rahul S Patwardhan
mathjax: true
---

* content
{:toc}

##### Abstract
Enterprise level software is implemented using multi-layer architecture. These layers are often implemented using de-coupled solutions with millions of lines of code. Programmers often have to track and debug a function call from user interface layer to the data access layer while troubleshooting an issue. They have to inspect the code based on search results or use design documents to construct the call graph. This process is time consuming and laborious. The development environment tools are insufficient or confined to analyzing only the code in the loaded solution. This paper proposes a method to construct a call graph of the call across several layers of the code residing in different code bases to help programmers better understand the design and architecture of the software. The signatures of class, methods, and properties were evaluated and then matched against the code files. A graph of matching functions was created. The recursive search stopped when there were no matches or the data layer code was detected. The method resulted in 78.26% accuracy when compared with manual search.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.04594](https://arxiv.org/abs/1610.04594)

##### PDF
[https://arxiv.org/pdf/1610.04594](https://arxiv.org/pdf/1610.04594)

