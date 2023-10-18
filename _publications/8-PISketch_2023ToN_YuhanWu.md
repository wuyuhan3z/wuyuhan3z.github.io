---
title: "Finding Persistent and Infrequent Flows"
collection: publications
permalink: /publication/8-PISketch_2023ToN_YuhanWu
excerpt: ' Finding persistent and low-active activity periods is very helpful in practice, for example to detect intrusion activities. Most of the literature focuses on finding persistent flows or frequent flows. No previous work is able to find persistent and infrequent flows. In this paper, we propose a novel sketch data structure, PISketch, to find persistent and infrequent flows in real time. The key idea of PISketch is to define a weight and its Reward and Penalty System for each flow to combine and balance the information of both persistency and infrequency, and to keep high-weighted flows in a limited space through a strategy. We implement PISketch on P4, FPGA, and CPU platforms, and compare the performance of PISketch with two strawman solutions (On-Off + CM sketch, and PIE + CM sketch), in terms of finding persistent and infrequent flows. Our experimental results demonstrate the advantage of PISketch, by comparing it to two strawman solutions: 1) The F1 Score of PISketch is around 22.1% and 57.6% higher than two strawman solutions, respectively; 2) The Average Relative Error (ARE) of PISketch is around 820.9 (up to 1188.8) and 126.2 (up to 265.6) times lower than two strawman solutions, respectively; 3) The insertion throughput of PISketch is around 1.23 and 16.5 times higher than two strawman solutions, respectively. Moreover, we implement two concrete cases of PISketch through end-to-end experiments. All of our codes are available at GitHub. '
Author: 'Zhuochen Fan, Zhoujing Hu, Yuhan Wu, Jiarui Guo, Sha Wang, Wenrui Liu,  Tong Yang, Yaofeng Tu, Steve Uhlig.'
date: 2023-04-25
venue: 'Transactions on Networking (ToN) 2023'
paperurl: 'http://wuyuhan3z.github.io/files/8-PISketch_2023ToN_YuhanWu.pdf'


---

   
