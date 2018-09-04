---
title: "Partial Transfer Learning with Selective Adversarial Networks"
collection: publications
permalink: /publications/SAN18
venue: "Conference on Computer Vision and Pattern Recognition (CVPR), 2018"
date: 2017-10-21
citation: '<b>Zhangjie Cao</b>, Mingsheng Long, Jianmin Wang, Michael I. Jordan. <i>Conference on Computer Vision and Pattern Recognition</i> <b>CVPR 2018</b>.'
---

[[Conference Version]](http://caozhangjie.github.io/files/SAN18.pdf)
[[Arxiv]](https://arxiv.org/abs/1707.07901)
[[Code]](https://github.com/thuml/SAN)
[[Poster]](http://caozhangjie.github.io/files/SAN18_poster.pdf)

## Abstract
Adversarial learning has been successfully embedded into deep networks to learn transferable features, which reduce distribution discrepancy between the source and target domains. Existing domain adversarial networks assume fully shared label space across domains. In the presence of big data, there is strong motivation of transferring both classification and representation models from existing large-scale domains to unknown small-scale domains. This paper introduces partial transfer learning, which relaxes the shared label space assumption to that the target label space is only a subspace of the source label space. Previous methods typically match the whole source domain to the target domain, which are prone to negative transfer for the partial transfer problem. We present Selective Adversarial Network (SAN), which simultaneously circumvents negative transfer by selecting out the outlier source classes and promotes positive transfer by maximally matching the data distributions in the shared label space. Experiments demonstrate that our models exceed state-of-the-art results for partial transfer learning tasks on several benchmark datasets.
