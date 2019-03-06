---
title: "Universal Domain Adaptation"
collection: publications
permalink: /publications/UDA19
venue: "Conference on Computer Vision and Pattern Recognition (CVPR), 2019"
date: 2019-06-16
citation: 'Kaichao You, <b>Zhangjie Cao</b>, Mingsheng Long, Jianmin Wang, Michael I. Jordan. <i>Conference on Computer Vision and Pattern Recognition</i> <b>CVPR 2019</b>.'
---

[[Conference Version]] Available after Camera Ready
[[Arxiv]] Available Soon
[[Code]] Available Soon
[[Poster]] Available Soon

## Abstract
Domain adaptation aims to close domain gap and transfer knowledge across domains. Existing domain adaptation methods assume some prior knowledge on the relationship between the label sets of the source and target domains, which limits their application in the wild. This paper introduces Universal Domain Adaptation (UDA) which imposes no prior knowledge on the label sets. For a given source label set and an arbitrary target label set, they may contain a common label set and hold a private label set respectively, bringing up an additional category gap. UDA requires a model to (1) either classify the target sample correctly if it is associated with a label in the common label set, or (2) mark it as “unknown” otherwise. More importantly, a UDA model should work stably against a wide spectrum of commonness (the proportion of the common label set) so that it can handle real-world problems. UDA extends closed set, partial and open set domain adaptation settings that require prior knowledge on label sets. To solve the universal domain adaptation problem, we propose Universal Adaptation Network (UAN). It learns transferability of samples to discriminate the common label set and the label sets private to each domain. The proposed UAN can promote the adaptation from source samples to target samples in the common label set, and recognize the “unknown” samples successfully. A thorough evaluation shows that our approach outperforms the state of the art closed set, partial and open set domain adaptation methods in most UDA settings.
