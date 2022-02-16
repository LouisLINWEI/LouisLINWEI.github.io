---
title: "Efficient network dismantling through genetic algorithms"
collection: publications
permalink: /publication/Efficient network dismantling through genetic algorithms
date: 2021-11-19
venue: 'Soft Computing'
paperurl: 'http://louislinWei.github.io/files/SOCO.pdf'
---
Throughout the past decades, network dismantling gained an increasing interest by the research community, given tremendous importance of robust socio-technical systems. The problem of optimally dismantling a given network is provably NP-hard. Accordingly, existing studies on network dismantling resort to various heuristics, including the use of node centralities and finely tuned decycling and cutting techniques. However, it is known that these existing techniques largely lack the optimal baseline. Particularly, these techniques perform bad when compared to (expensive-to-compute) betweenness-based attacks. Therefore, there is a strong need for developing scalable, yet accurate attacking methods for being able to understand the robustness of large, real-world complex systems. In this study, we propose a novel network attack technique based on genetic algorithms. In order to develop a scalable framework, we first design an exact method for measuring the effectiveness of an attack, requiring *O*(|*E*|) time, where |*E*| is the number of edges in the network. Since this algorithm runs in linear time of the network size, it can scale up well for very large networks. Second, we develop and analyze a collection of genetic population constructors, which aim at providing a rich set of initial genetic material to the framework. Several genetic operators are proposed, which preferably select previously critical nodes to be attacked first. Finally, we evaluate our framework on a wide range of real-world networks. Results show that our novel technique significantly outperforms the state-of-the-art methods, providing an interesting sweet spot between attack quality and computational complexity. We believe that our work contributes toward the scalable robustness estimation of complex networks, and that the perspective of using non-deterministic methods will inspire future research in this domain.

[Download paper here](http://academicpages.github.io/files/paper2.pdf)



