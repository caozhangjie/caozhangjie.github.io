---
title: "Transfer Adversarial Hashing for Hamming Space Retrieval"
collection: publications
permalink: /publications/TAH18
venue: "AAAI Conference on Artificial Intelligence (AAAI), 2018"
date: 2017-10-21
citation: '<b>Zhangjie Cao</b>, Mingsheng Long, Chao Huang, Jianmin Wang. <i>AAAI Conference on Artificial Intelligence</i> <b>AAAI 2018</b>.'
---

[[Conference Version]](http://caozhangjie.github.io/files/TAH18.pdf)
[[Arxiv]](https://arxiv.org/abs/1712.04616)
[[Code]](https://github.com/thuml/TAH)

## Abstract
Hashing is widely applied to large-scale image retrieval due to the storage and retrieval efficiency. Existing work on deep hashing assumes that the database in the target domain is identically distributed to the training set in the source domain for hash function learning. This paper relaxes this assumption to a transfer retrieval setting, which allows that the database and the training set are from different but relevant domains. However, the transfer retrieval problem will introduce two technical difficulties: first, the hash model trained on the source domain cannot work well on the target domain due to the large distribution shift; second, the domain gap makes it hard to concentrate the database points to be within a small Hamming ball. As a consequence, the performance of hashing methods for transfer retrieval within Hamming Radius 2 degrades significantly. This paper presents Transfer Adversarial Hashing (TAH), a new hybrid deep architecture that incorporates a pairwise $t$-distribution cross-entropy loss to learn concentrated hash codes and an adversarial network to align the data distributions between the source and target domain. TAH can generate compact transfer hash codes for efficient image retrieval on both the source and target domains. Comprehensive empirical study validates that the proposed TAH yields state of the art retrieval performance on standard multimedia benchmarks NUS-WIDE and VisDA2017.
