---
title: "KVSAgg: Secure Aggregation of Distributed Key-Value Sets."
collection: publications
permalink: /publication/7-KVSAGG_2023ICDE_YuhanWu
excerpt: ' In global data analysis, the central server needs the global statistic of the user data stored in local clients. In such cases, an Honest-but-Curious central server might put user privacy at risk in trying to collect individual statistics of each user. In response, the secure aggregation provides a solution for calculating global statistics without revealing users' privacy data. However, existing secure aggregation protocols only focus on the data in the form of vectors or common sets, which limits their application scope. We formalize a general problem---key-value set secure aggregation---that not only includes secure vector aggregation and private set union but also supports more applications. To address the proposed problem, we devise our solution (called the KVSAgg framework) that promises satisfactory performance in security, efficiency, and accuracy. Our key technique is a homomorphic transform algorithm (called HyperIBLT) that is not only capable of bidirectionally transforming data between key-value sets and vectors, but also able to transform sum operation of sets to addition of vectors. We implement KVSAgg on both CPU and GPU platforms and perform the evaluation on three use cases including federated learning, distributed data counting, and finding global hot items. Compared with our baselines, KVSAgg simultaneously achieves the best security, efficiency higher by orders of magnitude, and zero-error in nearly all cases. All codes are open-source anonymously. '
Author: 'Yuhan Wu, Siyuan Dong, Yi Zhou, Yikai Zhao, Fangcheng Fu,  Tong Yang, Chaoyue Niu, Fan Wu, Bin Cui.'
date: 2023-04-03
venue: 'International Conference on Data Engineering (ICDE) 2023'
paperurl: 'http://wuyuhan3z.github.io/files/7-KVSAGG_2023ICDE_YuhanWu.pdf'


   