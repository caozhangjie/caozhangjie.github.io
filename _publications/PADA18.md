---
title: "Partial Adversarial Domain Adaptation"
collection: publications
permalink: /publications/PADA18
venue: "European Conference on Computer Vision (ECCV), 2018"
date: 2017-10-21
citation: '<b>Zhangjie Cao</b>, Lijia Ma, Mingsheng Long, Jianmin Wang. <i>European Conference on Computer Vision</i> <b>ECCV 2018</b>.'
---

[[Conference Version]](http://caozhangjie.github.io/files/PADA18.pdf)
[[Arxiv]](https://arxiv.org/abs/1808.04205)
[[Code]](https://github.com/thuml/PADA)
[[Poster]](http://caozhangjie.github.io/files/PADA18_poster.pdf)

## Abstract
Domain adversarial learning aligns the feature distributions across the source and target domains in a two-player minimax game. Existing domain adversarial networks generally assume identical label space across different domains. In the presence of big data, there is strong motivation of transferring deep models from existing big domains to unknown small domains. This paper introduces partial domain adaptation as a new domain adaptation scenario, which relaxes the fully shared label space assumption to that the source label space subsumes the target label space. Previous methods typically match the whole source domain to the target domain, which are vulnerable to negative transfer for the partial domain adaptation problem due to the large mismatch between label spaces. We present Partial Adversarial Domain Adaptation (PADA), which simultaneously alleviates negative transfer by down-weighing the data of outlier source classes for training both source classifier and domain adversary, and promotes positive transfer by matching the feature distributions in the shared label space. Experiments show that PADA exceeds state-of-the-art results for partial domain adaptation tasks on several datasets.
