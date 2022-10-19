---
title: "PISketch: Finding Persistent and Infrequent Flows"
collection: publications
permalink: /publication/5-PISketch_2022FFSPIN_YuhanWu
excerpt: ' Data stream mining over a sliding window is a fundamental problem in many applications, such as financial data trackers, intrusion detection and QoS. To meet the demand for high throughput of high speed data streams, hardware platforms (FPGA/ASIC) have been designed. These hardware platforms have three constraints for algorithms running on, which are 1) small memory usage 2) single stage memory access and 3) limited concurrent memory access. Algorithms perfectly fit in with these constraints will enable a highest utilization of these hardware platforms. However, no existing sliding window algorithm is specifically designed for hardware platforms. In this paper, we propose the Sliding Hardware Estimator (SHE), which is a generic framework that extends existing fixed window algorithms to sliding windows for hardware platforms. The key idea of SHE is that, during insertions we approximately delete out-dated information with little time and space overhead, while during queries we design sophisticated techniques to minimize error. We have fully implemented our SHE on FPGA, achieving a throughput of 544 Mips. We apply SHE to four typical data stream mining tasks. Experimental results show that, when compared with the state-of-the-art which cannot be implemented in hardware, SHE reduces the error by up to 100 times in membership queries. All related source codes are anonymously released at Github. '
Author: 'Zhuochen Fan, Zhoujing Hu, Yuhan Wu, Jiarui Guo, Wenrui Liu,  Tong Yang, Hengrui Wang, Yifei Xu, Steve Uhlig, Yaofeng Tu.'
date: 2022-08-22
venue: 'ACM SIGCOMM Workshop on FFSPIN 2022.'
paperurl: 'http://wuyuhan3z.github.io/files/5-PISketch_2022FFSPIN_YuhanWu.pdf'

 
   
---

<!-- citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).' -->

<!-- This paper is about the number 1. The number 2 is left for future work. -->

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
