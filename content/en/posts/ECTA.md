---
title: "When Feasible Solutions Become a Trap: Initialization Strategies for EDAs in the Traveling Tournament Problem"
date: "2026-10-13T10:00:00-03:00"
tags: ["Traveling Tournament Problem", "Estimation of Distribution Algorithms"]
title-images: []
ending-images: []
author: "GuilhermeNakahata"
draft: false
table-of-contents: true
toc-auto-numbering: true
---

I’ll be presenting this paper at ECTA 2026 in Angers, France, on October 28–30. It looks at how different starting solutions affect Estimation of Distribution Algorithms (EDAs) for the Traveling Tournament Problem.

<!--more-->

We compare feasible, partially feasible, and infeasible initial populations using two types of EDAs. We also study the effects of penalty strength and local search, in our experiments, initialization had more influence on the search than penalty strength, while local search provided much of the improvement on larger instances.

![Descrição da imagem](/images/ttp.png)

You can also read our earlier work on generating feasible initial schedules for the TTP [here](https://guilhermenkht.github.io/TTP_ConstructiveMethod/).