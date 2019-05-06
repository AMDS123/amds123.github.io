---
layout: post
title: "On Implementation of a Safer C Library, ISO/IEC TR 24731"
date: 2009-07-27 04:44:56
categories: arXiv_CV
tags: arXiv_CV
author: Marc-André Laverdière, Serguei A. Mokhov, Djamel Benredjem
mathjax: true
---

* content
{:toc}

##### Abstract
The functions standardized as part of ISO C 1999 and their addendums improved very little the security options from the previously available library. The largest flaw remained that no function asked for the buffer size of destination buffers for any function copying data into a user-supplied buffer. According to earlier research we performed, we know that error condition handling was the first solution to security vulnerabilities, followed by precondition validation. The standard C functions typically perform little precondition validation and error handling, allowing for a wide range of security issues to be introduced in their use. ISO/IEC TR 24731, titled as "TR 24731: Safer C library functions", defines 41 new library functions for memory copying, string handling (both for normal and wide character strings), time printing, sorting, searching etc. Another innovation it brings is a constraint handling architecture, forcing error handling when certain security-related preconditions are violated when the functions are called. It also specifies the null-termination of all strings manipulated through its function and introduces a new unsigned integer type that helps preventing integer overflows and underflows. It is currently implemented by Microsoft as part of their Visual Studio 2005 and above. We examine the architecture of our implementation of ISO/IEC TR 24731. We first introduce our architectural philosophy before informing the reader about the Siemens Four View Model, an architectural methodology for the conception of large-scale software systems. Afterwards, we examine each of the view, as architected for our library. Finally, we conclude with other software engineering matters that were of high importance in the development of our implementation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0906.2512](https://arxiv.org/abs/0906.2512)

##### PDF
[https://arxiv.org/pdf/0906.2512](https://arxiv.org/pdf/0906.2512)

