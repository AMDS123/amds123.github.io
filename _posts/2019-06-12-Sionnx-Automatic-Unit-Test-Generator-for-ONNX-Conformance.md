---
layout: post
title: "Sionnx: Automatic Unit Test Generator for ONNX Conformance"
date: 2019-06-12 02:59:16
categories: arXiv_AI
tags: arXiv_AI
author: Xinli Cai, Peng Zhou, Shuhan Ding, Guoyang Chen, Weifeng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Open Neural Network Exchange (ONNX) is an open format to represent AI models and is supported by many machine learning frameworks. While ONNX defines unified and portable computation operators across various frameworks, the conformance tests for those operators are insufficient, which makes it difficult to verify if an operator's behavior in an ONNX backend implementation complies with the ONNX standard. In this paper, we present the first automatic unit test generator named Sionnx for verifying the compliance of ONNX implementation. First, we propose a compact yet complete set of rules to describe the operator's attributes and the properties of its operands. Second, we design an Operator Specification Language (OSL) to provide a high-level description for the operator's syntax. Finally, through this easy-to-use specification language, we are able to build a full testing specification which leverages LLVM TableGen to automatically generate unit tests for ONNX operators with much large coverage. Sionnx is lightweight and flexible to support cross-framework verification. The Sionnx framework is open-sourced in the github repository (this https URL).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05676](https://arxiv.org/abs/1906.05676)

##### PDF
[https://arxiv.org/pdf/1906.05676](https://arxiv.org/pdf/1906.05676)

