---
title: "Elastic Bloom Filter: Deletable and ExpandableFilter Using Elastic Fingerprints."
collection: publications
permalink: /publication/2-ElasticBF_2021TC_YuhanWu
excerpt: 'The Bloom filter, answering whether an item is in a set, has achieved great success in various fields, including networking, databases, and bioinformatics. However, the Bloom filter has two main shortcomings: no support of item deletion and no support of expansion. Existing solutions either support deletion at the cost of using additional memory, or support expansion at the cost of increasing the false positive rate and decreasing the query speed. Unlike existing solutions, we propose the Elastic Bloom filter (EBF) to address the two shortcomings simultaneously. Importantly, when EBF expands, the false positives decrease. Our key technique is Elastic Fingerprints, which dynamically absorb and release bits during compression and expansion. To support deletion, EBF can first delete the corresponding fingerprint and then update the corresponding bit in the Bloom filter. To support expansion, Elastic Fingerprints release bits and insert them to the Bloom filter. Our experimental results show that the Elastic Bloom filter significantly outperforms existing works.'
author: 'Yuhan Wu, Jintao He, Shen Yan, Jianyu Wu, Tong Yang, Olivier Ruas, Gong Zhang, Bin Cui.'
date: 2021-03-22
venue: 'March 22 '
paperurl: 'http://wuyuhan3z.github.io/files/2-ElasticBF_2021TC_YuhanWu.pdf'


---

<!-- citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).' -->

<!-- This paper is about the number 1. The number 2 is left for future work. -->

[Download paper here](http://academicpages.github.io/files/2-ElasticBF_2021TC_YuhanWu.pdf)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
