---
layout: post
title: "GASTAP: A Gas Analyzer for Smart Contracts"
date: 2018-11-22 13:19:07
categories: arXiv_CL
tags: arXiv_CL
author: Elvira Albert, Pablo Gordillo, Albert Rubio, Ilya Sergey
mathjax: true
---

* content
{:toc}

##### Abstract
Gas is a measurement unit of the computational effort that it will take to execute every single operation that takes part in the Ethereum blockchain platform. Each instruction executed by the Ethereum Virtual Machine (EVM) has an associated gas consumption specified by Ethereum. If a transaction exceeds the amount of gas allotted by the user (known as gas limit), an out-of-gas exception is raised. There is a wide family of contract vulnerabilities due to out-of-gas behaviours. We report on the design and implementation of GASTAP, a Gas-Aware Smart contracT Analysis Platform, which takes as input a smart contract (either in EVM, disassembled EVM, or in Solidity source code) and automatically infers sound gas upper bounds for all its public functions. Our bounds ensure that if the gas limit paid by the user is higher than our inferred gas bounds, the contract is free of out-of-gas vulnerabilities.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10403](https://arxiv.org/abs/1811.10403)

##### PDF
[https://arxiv.org/pdf/1811.10403](https://arxiv.org/pdf/1811.10403)

