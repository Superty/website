---
title: "Curriculum Vitae"
date: 2025-12-23
draft: false
---

<div class="cv-section">

## Professional Summary

Experience in **performance engineering and algorithms** across the stack:

- implemented & maintain the integer linear programming (ILP) solver in MLIR [[code sample]](https://github.com/llvm/llvm-project/blob/main/mlir/lib/Analysis/Presburger/Simplex.cpp#L1996) [[library]](https://github.com/llvm/llvm-project/tree/main/mlir/lib/Analysis/Presburger)
- optimized an ILP solver for compiler workloads using C++ templates & AVX-512 vector intrinsics to achieve a **3.6x speedup over SOTA** [[Distinguished Paper at OOPSLA]](https://2021.splashcon.org/details/splash-2021-oopsla/66/FPL-Fast-Presburger-Arithmetic-through-Transprecision)
- research on **cache hierarchy miss rate prediction** [[paper at PLDI]](https://dl.acm.org/doi/10.1145/3656452)
- designed **asymptotically better ILP algorithms** for our compiler use-case [[paper at CAV]](https://link.springer.com/chapter/10.1007/978-3-031-65627-9_14)
- performance debugging: reading flamegraphs, LLVM IR, x86-64 assembly, architecture diagrams, ...
- benchmarking with [PMCs](https://www.amd.com/content/dam/amd/en/documents/epyc-technical-docs/programmer-references/58550-0.01.pdf), minimizing noise from frequency scaling, SMT, context switches, ...

</div>
<div class="cv-section">

## Experience <div class="experience-filters"><label><input type="radio" name="exp-filter" class="tag-filter" value="systems" checked> Performance &amp; Compilers</label><label><input type="radio" name="exp-filter" class="tag-filter" value="ai-safety"> AI Safety</label><label><input type="radio" name="exp-filter" class="tag-filter" value="theory"> Theory</label></div>

<div class="experience-item" data-tags="systems,theory">

### Student Researcher at Google DeepMind (Paris)
**November 2023 — February 2024**

Worked on static analysis for tiled linear algebraic kernels. I developed asymptotically faster algorithms for ILP for subclasses relevant to compilers, with proofs of efficiency & correctness. [[Paper @ CAV]](https://link.springer.com/chapter/10.1007/978-3-031-65627-9_14)

</div>


<div class="experience-item" data-tags="systems">

### Lead Maintainer of the MLIR Presburger Library
**2020 — Present**

[[commits]](https://github.com/llvm/llvm-project/commits/main?author=superty) [[reviews]](https://github.com/search?q=repo\%3Allvm\%2Fllvm-project+\%22Reviewed+By\%3A+arjunp\%22\&type=commits\&p=1) [[older reviews]](https://github.com/llvm/llvm-project/pulls?q=is\%3Apr+reviewed-by\%3Asuperty+) [[website]](https://grosser.science/FPL)

- Lead maintainer of the Presburger library of the LLVM/MLIR open-source compiler framework
- Reviewed 100+ pull requests and worked with a team of up to four other contributors
- Added support for multiprecision integers to LLVM based on APInt & optimized it for our workload

</div>



<div class="experience-item" data-tags="systems">

### Research Intern at ETH Zürich
**August 2019 — April 2020**

Wrote the MLIR Presburger library (see above) and worked on papers published at OOPSLA '20 and '21.

</div>

<div class="experience-item" data-tags="theory">

### Research Intern at TIFR, Mumbai
**May — July 2018**

Studied approximation algorithms and hardness of approximation (via probabilistically checkable proofs).

</div>

<div class="experience-item" data-tags="systems">

### Software Engineering Intern at Google Zürich
**May — August 2017**

Worked on performance optimizing RPC calls in a C++ microservices framework.

</div>

<div class="experience-item" data-tags="ai-safety,theory">

### Visiting Researcher at the Alignment Research Center
**August 2025**

<p class="exp-desc" data-tags="theory">Worked with a team of math/theoretical CS PhDs. In two weeks, I found a counterexample for a proposed algorithm, showing it yielded poor approximations. The problem had been open for two months.</p>
<p class="exp-desc" data-tags="ai-safety">AI safety research towards mechanistic anomaly detection. Specifically, did theoretical research on a toy model involving matrix permanent estimation.</p>

</div>

<div class="experience-item" data-tags="ai-safety,theory">

### Research Scholar at the MATS Program
**February — May 2024**

<p class="exp-desc" data-tags="theory">Worked on Markov decision process theory.</p>
<p class="exp-desc" data-tags="ai-safety">AI safety research on Vanessa Kosoy's learning-theoretic agenda. Specifically, I worked on MDP theory.</p>

</div>

<div class="experience-item" data-tags="theory">

### Undergraduate Research at IIIT Hyderabad
**2017 — 2018**

Worked on hypergraph theory and communication complexity.

</div>

</div>

<div class="cv-section">

## Achievements

[Bronze Medal](https://stats.ioinformatics.org/people/5608) at the **International Olympiad in Informatics (IOI) 2015.**

[World Finalist](https://cphof.org/profile/icpc:Arjun%20Pitchanathan) at the **International Collegiate Programming Competition (ICPC) 2020.**

</div>

<div class="cv-section collapsible">

## Publications

---

Strided Difference Bound Matrices.
[CAV&nbsp;2024.](https://link.springer.com/chapter/10.1007/978-3-031-65627-9_14)
<br>
*<span class="me">Arjun&nbsp;Pitchanathan</span>, Albert&nbsp;Cohen, Oleksandr&nbsp;Zinenko, Tobias&nbsp;Grosser.*

---

Falcon: A Scalable Analytical Cache Model.
[PLDI&nbsp;2024.](https://dl.acm.org/doi/10.1145/3656452)
<br>
*<span class="me">Arjun&nbsp;Pitchanathan</span>, Kunwar&nbsp;Grover, Tobias&nbsp;Grosser.*

---

FPL: Fast Presburger Arithmetic through Transprecision.
[OOPSLA&nbsp;2021.](https://doi.org/10.1145/3485539)
<span class="award">Distinguished&nbsp;Paper&nbsp;Award.</span>
<br>
*<span class="me">Arjun&nbsp;Pitchanathan</span>, Christian&nbsp;Ulmann, Michel&nbsp;Weber, Torsten&nbsp;Hoefler, Tobias&nbsp;Grosser.*

---

Fast Linear Programming through Transprecision Computing on Small and Sparse Data.
[OOPSLA&nbsp;2020.](https://doi.org/10.1145/3428263)
<span class="award">[HiPEAC&nbsp;Tech&nbsp;Transfer&nbsp;Award.](https://www.hipeac.net/news/6975/announcing-winners-hipeac-tech-transfer-awards-2021/)</span>
*Tobias&nbsp;Grosser, Theodoros&nbsp;Theodoridis, Maximilian&nbsp;Falkenstein, <span class="me">Arjun&nbsp;Pitchanathan</span>, Michael&nbsp;Kruse, Manuel&nbsp;Rigger, Zhendong&nbsp;Su, Torsten&nbsp;Hoefler.*

</div>

<div class="cv-section collapsible collapsed">

## Other Research

---

Provably Efficient LRU Cache Modeling.
Under preparation.
<br>
*<span class="me">Arjun&nbsp;Pitchanathan</span> and Tobias&nbsp;Grosser.*

---

Compositional Polytope MDPs.
Under preparation.
<br>
*<span class="me">Arjun&nbsp;Pitchanathan</span> and Vanessa&nbsp;Kosoy.*

---

On the Simple Quasi Crossing Number of K₁₁.
[GD&nbsp;2019 (poster with extended abstract).](https://link.springer.com/content/pdf/bbm:978-3-030-35802-0/1)
<br>
*Arjun&nbsp;Pitchanathan and Saswata&nbsp;Shannigrahi.*

---

Improved Encoding and Counting of Uniform Hypertrees.
[Manuscript.](https://arxiv.org/abs/1711.03335v4)
<br>
*Arjun&nbsp;Pitchanathan and Saswata&nbsp;Shannigrahi.*

---

Decision-Theoretic Compression and Value-Aware Measures of Information and Noise.
[Manuscript.](https://github.com/Superty/dtcompress/blob/master/dtcompress_draft.pdf)
<br>
*Tushant&nbsp;Jha, <span class="me">Arjun&nbsp;Pitchanathan</span>, and Kannan&nbsp;Srinathan.*

</div>

<div class="cv-section">

## Education

**2024 — present:** Visiting PGR Student at the **University of Cambridge** (Advisor: Tobias Grosser)<br>
**2022 — present:** PhD in Informatics at the **University of Edinburgh** (Advisor: Tobias Grosser)<br>
Thesis title: Efficient Static Analysis for Neural Networks

*I did the second half of my PhD in Cambridge, as my advisor moved there.*

**2015 — 2021:** BTech and MS in Computer Science and Engineering at **IIIT Hyderabad**

</div>

<div class="cv-section collapsible collapsed">

## Talks

I have given talks at:

- academic conferences: OOPSLA '21 [[online version]](https://www.youtube.com/watch?v=UibEvel177w), PLDI '22, [PLDI '24](https://www.youtube.com/watch?v=ALOvruhw8sI)
- the Polyhedral Compilation Workshop (IMPACT) at HiPEAC '22
- LLVM Developer Meetings: US '21, Europe '22, US '22 (MLIR summit), Europe '24, US '24
</div>

<div class="cv-section divided collapsible collapsed">

## Professional Service

**Reviewer** for **ACM Transactions on Architecture and Code Optimization**

**Program Committee Member** for **IMPACT '23**,<br>
the 13th International Workshop on Polyhedral Compilation Techniques.

**Artifact Evaluation Committee Member** for **CC '24**,<br>
the ACM SIGPLAN 33rd International Conference on Compiler Construction.

</div>

<div class="cv-section collapsible collapsed">

## Teaching

### Teaching Assistant at IIIT Hyderabad
**Monsoon 2018, Spring 2019 semesters**

Served as a TA for the cryptography and algorithms courses.

### Coach at the Indian IOI Training Camp
**2016, 2018**

Part of the team that took classes, prepared problems and test data, and evaluated students' solutions at the International Olympiad in Informatics Training Camp (IOITC), which is held to select a team to represent India at the International Olympiad in Informatics (IOI).

</div>

<div class="cv-section collapsible collapsed">

## Undergraduate Activities

### Coordinator of the Competitive Programming Club
**Monsoon 2017; Spring 2018**

One of two coordinators for the Competitive Programming Club that year. This involved conducting events and teaching topics in computer science, especially involving algorithms and data structures.

### Student Systems Administrator
**Monsoon 2017**

Had the opportunity to get some hands-on experience in system administration by helping out the university's full-time staff.

### Copy-editor at the Ping! Student Magazine
**Monsoon 2017**

- Copy-edited all the articles in the Monsoon 2017 issue
- shepherded some articles through the writing process
- co-authored an article on the necessity of UBI after AGI
</div>

<footer class="cv-footer">
Built with <a href="https://claude.ai">Claude</a> using <a href="https://gohugo.io">Hugo</a><span class="accent">.</span>
</footer>
