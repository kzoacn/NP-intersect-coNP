# 论文计算复杂性与算法问题分类总结表

根据相关文献汇总，以下是计算问题在各复杂度类（NP ∩ coNP 及其变种 AM ∩ coAM）以及亚指数时间（SUBEXP）、准多项式时间（QuasiP）和多项式时间（P）算法中的分类总结。

注：其实应该使用SUBE这个记号表达亚指数时间

| 问题 (Problem) | in NP (AM) | in coNP (coAM) | in SUBEXP | in QuasiP | in P | 论文来源 / 引用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **素性判定问题 (Primality Testing)** | ✓ | ✓ | ✓ | ✓ | ✓ | [AKS02], [Pra75] |
| **整数分解问题 (Integer Factorization)** | ✓ | ✓ | ✓ | ? | ? | [Pom84], [LLMP90], [Sho94] |
| **离散对数问题 (Discrete Logarithm)** | ✓ | ✓ | ✓* | ✓* | ? | [Adl79], [KW22] (For Finite Field with fix char), [Sho94] |
| **验证代数数域的类数** | ✓ | ✓ (GRH) | ✓ | ? | ? | [HM89], [Thi94] |
| **多项式代数依赖性测试(Algebraic Dependence)** | ✓ (AM) | ✓ (coAM) | ? | ? | ? | [GSS18] |
| **图同构问题 (Graph Isomorphism)** | ✓ | ✓ (coAM) | ✓ | ✓ | ? |  [BL83],[Bab85],[Bab16] |
| **群同构 (Group Isomorphism)** | ✓ | ✓ (coAM) | ✓ | ✓ | ? | [Mil78], [Bab85] |
| **环同构问题 (Ring Isomorphism)** | ✓ | ✓ (coAM) | ? | ? | ? | [KS06] |
| **Tensor Isomorphism** | ✓ | ✓ (coAM,*) | ? | ? | ? | [GQ21] |
| **Code Equivalence** | ✓ | ✓ (coAM) | ? | ? | ? | [PR02] |
| **GapCVP ($\sqrt{n}$-近似)** | ✓  | ✓  | ? | ? | ? | [AR04],[GG98] |
| **GapSVP ($\sqrt{n}$-近似)** | ✓  | ✓  | ? | ? | ? | [AR04],[GG98] |
| **线性规划 (Linear Programming)** | ✓ | ✓ | ✓ | ✓ | ✓ | [Kar84], [Kha79],[Far02] |
| **奇偶博弈 (Parity games)** | ✓ | ✓ | ✓ | ✓ | ? | [Jur98] , [BSV03] ; [CJK+17], [EJ91] |
| **简单随机博弈 (Simple Stochastic Games)** | ✓ | ✓ | ✓ | ? | ? | [Con92] , [Lud95]  |
| **平均收益博弈 (Mean-payoff games)** | ✓ | ✓ | ✓ | ? | ? | [ZP96] , [Lud95] |
| **ARRIVAL问题** | ✓ | ✓ | ✓ | ? | ? | [DGK+17],  [GHH21] |
| **三维球面识别** | ✓ | ✓ (GRH) | ? | ? | ? | [Sch11], [Zen18] |
| **Unknot问题 (Unknotting Problem)** | ✓ | ✓ | ✓ | ✓ | ? | [HLP99] ;  [Lac21] |
 
---
## Remarks

- 离散对数问题 (Discrete Logarithm) 的准多项式时间算法固定特征ps, (pn)^(polylog(n))
- 有限域上的Tensor Isomorphism 在 NP∩coNP中


## 参考文献

* **[Adl79]** Adleman, L. (1979, October). A subexponential algorithm for the discrete logarithm problem with applications to cryptography. In Proceedings of the 20th Annual Symposium on Foundations of Computer Science (pp. 55-60).
* **[AKS02]** Agrawal, M., Kayal, N., & Saxena, N. (2004). PRIMES is in P. Annals of mathematics, 781-793.
* **[AR04]** Aharonov, D., & Regev, O. (2005). Lattice problems in NP∩ coNP. Journal of the ACM (JACM), 52(5), 749-765.
* **[BL83]** Babai, L., & Luks, E. M. (1983, December). Canonical labeling of graphs. In Proceedings of the fifteenth annual ACM symposium on Theory of computing (pp. 171-183).
* **[Bab85]** Babai, L. (1985, December). Trading group theory for randomness. In Proceedings of the seventeenth annual ACM symposium on Theory of computing (pp. 421-429).
* **[Bab16]** Babai, L. (2016, June). Graph isomorphism in quasipolynomial time. In Proceedings of the forty-eighth annual ACM symposium on Theory of Computing (pp. 684-697).
* **[BSV03]** Björklund, H., Sandberg, S., & Vorobyov, S. (2003). Randomized subexponential algorithms for parity games.
* **[CJK+17]** Calude, C. S., Jain, S., Khoussainov, B., Li, W., & Stephan, F. (2017, June). Deciding parity games in quasipolynomial time. In Proceedings of the 49th Annual ACM SIGACT Symposium on Theory of Computing (pp. 252-263).
* **[Con92]** Condon, A. (1992). The complexity of stochastic games. Information and Computation, 96(2), 203-224.
* **[DGK+17]** Dohrau, J., Gärtner, B., Kohler, M., Matoušek, J., & Welzl, E. (2017). ARRIVAL: a zero-player graph game in NP∩ coNP. In A Journey Through Discrete Mathematics: A Tribute to Jiří Matoušek (pp. 367-374). Cham: Springer International Publishing.
* **[EJ91]** Emerson, E. A., & Jutla, C. S. (1991, October). Tree automata, mu-calculus and determinacy. In FoCS (Vol. 91, pp. 368-377).
* **[Far02]** Farkas, J. (1902). Theorie der einfachen Ungleichungen. Journal für die reine und angewandte Mathematik (Crelles Journal), 1902(124), 1-27.
* **[GG98]** Goldreich, O., & Goldwasser, S. (1998, May). On the limits of non-approximability of lattice problems. In Proceedings of the thirtieth annual ACM symposium on Theory of computing (pp. 1-9).
* **[KW22]** Kleinjung, T., & Wesolowski, B. (2022). Discrete logarithms in quasi-polynomial time in finite fields of fixed characteristic. Journal of the American Mathematical Society, 35(2), 581-624.
* **[GQ21]** Grochow, J., & Qiao, Y. (2023). On the complexity of isomorphism problems for tensors, groups, and polynomials I: tensor isomorphism-completeness. SIAM Journal on Computing, 52(2), 568-617.
* **[GHH21]** Gärtner, B., Haslebacher, S., & Hoang, H. P. (2021). A subexponential algorithm for ARRIVAL. arXiv preprint arXiv:2102.06427.
* **[HM89]** Hafner, J. L., & McCurley, K. S. (1989). A rigorous subexponential algorithm for computation of class groups. Journal of the American mathematical society, 2(4), 837-850.
* **[HLP99]** Hass, J., Lagarias, J. C., & Pippenger, N. (1999). The computational complexity of knot and link problems. Journal of the ACM (JACM), 46(2), 185-211.
* **[Jur98]** Jurdziński, M. (1998). Deciding the winner in parity games is in UP∩ co-UP. Information Processing Letters, 68(3), 119-124.
* **[KS06]** Kayal, N., & Saxena, N. (2006). Complexity of ring morphism problems. computational complexity, 15(4), 342-390.
* **[Kar84]** Karmarkar, N. (1984, December). A new polynomial-time algorithm for linear programming. In Proceedings of the sixteenth annual ACM symposium on Theory of computing (pp. 302-311).
* **[Kha79]** Khachiyan, L. G. (1979). *A polynomial algorithm in linear programming*.
* **[LLMP90]** Lenstra, A. K., Lenstra Jr, H. W., Manasse, M. S., & Pollard, J. M. (1990, April). The number field sieve. In Proceedings of the twenty-second annual ACM symposium on Theory of computing (pp. 564-572).
* **[Lac21]** Lackenby, M. (2021). The efficient certification of knottedness and Thurston norm. Advances in Mathematics, 387, 107796.
* **[Lud95]** Ludwig, W. (1995). A subexponential randomized algorithm for the simple stochastic game problem. Information and computation, 117(1), 151-155.
* **[PR02]** Petrank, E., & Roth, R. M. (2002). Is code equivalence easy to decide?. IEEE Transactions on Information Theory, 43(5), 1602-1604.
* **[Pom84]** Pomerance, C. (1984, April). The quadratic sieve factoring algorithm. In Workshop on the Theory and Application of of Cryptographic Techniques (pp. 169-182). Berlin, Heidelberg: Springer Berlin Heidelberg.
* **[Pra75]** Pratt, V. R. (1975). Every prime has a succinct certificate. SIAM Journal on Computing, 4(3), 214-220.
* **[GSS18]** Guo, Z., Saxena, N., & Sinhababu, A. (2019). Algebraic dependencies and PSPACE algorithms in approximative complexity over any field. Theory of Computing, 15(1), 1-30.
* **[Sch11]** Schleimer, S. (2011). Sphere recognition lies in NP. Low-dimensional and symplectic topology, 82(183-213), 1.
* **[Sho94]** Shor, P. W. (1994, November). Algorithms for quantum computation: discrete logarithms and factoring. In Proceedings 35th annual symposium on foundations of computer science (pp. 124-134). Ieee.
* **[Mil78]** Miller, G. L. (1978, May). On the nlog n isomorphism technique (a preliminary report). In Proceedings of the tenth annual ACM symposium on theory of computing (pp. 51-58).
* **[Thi94]** Thiel, Christoph. "Under the assumption of the Generalized Riemann Hypothesis verifying the class number belongs to NP∩ co-NP." International Algorithmic Number Theory Symposium. Berlin, Heidelberg: Springer Berlin Heidelberg, 1994.
* **[Zen18]** Zentner, R. (2018). Integer homology 3-spheres admit irreducible representations in SL (2, C).
* **[ZP96]** Zwick, U., & Paterson, M. (1996). The complexity of mean payoff games on graphs. Theoretical Computer Science, 158(1-2), 343-359.
