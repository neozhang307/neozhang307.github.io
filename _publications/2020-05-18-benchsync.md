---
title: "A Study of Single and Multi-device Synchronization Methods in Nvidia GPUs"
collection: conference
permalink: /publication/2022-5-18-benchsync
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2020-5-18~22
venue: '2020 IEEE International Parallel and Distributed Processing Symposium (IPDPS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9139854'
citation: 'L. Zhang, M. Wahib, H. Zhang and S. Matsuoka, "A Study of Single and Multi-device Synchronization Methods in Nvidia GPUs," 2020 IEEE International Parallel and Distributed Processing Symposium (IPDPS), New Orleans, LA, USA, 2020, pp. 483-493, doi: 10.1109/IPDPS47924.2020.00057.'
---

GPUs are playing an increasingly important role in general-purpose computing. Many algorithms require synchronizations at different levels of granularity in a single GPU. Additionally, the emergence of dense GPU nodes also calls for multi-GPU synchronization. Nvidia's latest CUDA provides a variety of synchronization methods. Until now, there is no full understanding of the characteristics of those synchronization methods. This work explores important undocumented features and provides an in-depth analysis of the performance considerations and pitfalls of the state-of-art synchronization methods for Nvidia GPUs. The provided analysis would be useful when making design choices for applications, libraries, and frameworks running on single and/or multi-GPU environments. We provide a case study of the commonly used reduction operator to illustrate how the knowledge gained in our analysis can be useful. We also describe our micro-benchmarks and measurement methods.
