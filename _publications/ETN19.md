---
title: "Learning to Transfer Examples for Partial Domain Adaptation"
collection: publications
permalink: /publications/ETN19
venue: "Conference on Computer Vision and Pattern Recognition (CVPR), 2019"
date: 2019-06-16
citation: '<b>Zhangjie Cao</b>*, Kaichao You*, Mingsheng Long, Jianmin Wang, Qiang Yang. <i>Conference on Computer Vision and Pattern Recognition</i> <b>CVPR 2019</b>.'
---

[[Conference Version]] Available after Camera Ready
[[Arxiv]] Available Soon
[[Code]] Available Soon
[[Poster]] Available Soon

## Abstract
Domain adaptation is critical for learning in new and unseen environments. With domain adversarial training, deep networks can learn disentangled and transferable features that effectively diminish the dataset shift between the source and target domains for knowledge transfer. In the era of Big Data, the ready availability of large-scale labeled datasets has stimulated wide interest in partial domain adaptation (PDA), which transfers a recognizer from a labeled large domain to an unlabeled small domain. It extends standard domain adaptation to the scenario where target labels are only a subset of source labels. Under the condition that target labels are unknown, the key challenge of PDA is how to transfer relevant examples in the shared classes to promote positive transfer, and ignore irrelevant ones in the specific classes to mitigate negative transfer. In this work, we propose a unified approach to PDA, Example Transfer Network (ETN), which jointly learns domain-invariant representations across source and target domains, and a progressive weighting scheme that quantifies the transferability of source examples while controlling their importances to the learning task in the target domain. A thorough evaluation on several benchmark datasets shows that our approach achieves state-of-the-art results for partial domain adaptation tasks.
