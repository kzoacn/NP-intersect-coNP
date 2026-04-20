# Are Languages in NP ∩ coNP Easy to Decide?


* NP ∩ coNP ⊆ SUBE ?
* NP ∩ coNP ⊆ QP ?
* NP ∩ coNP = P ?
* P = NP ?

| Problem | in NP (AM) | in coNP (coAM) | in SUBE | in QuasiP | in P | Paper Source / Citation |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Primality Testing** | ✓ | ✓ | ✓ | ✓ | ✓ | [AKS02], [Pra75] |
| **Integer Factorization** | ✓ | ✓ | ✓ | ? | ? | [Pom84], [LLMP90], [Sho94] |
| **Discrete Logarithm** | ✓ | ✓ | ✓* | ✓* | ? | [Adl79], [KW22], [Sho94] |
| **Class Number of Algebraic number fields** | ✓ | ✓ (GRH) | ✓ | ? | ? | [HM89], [Thi94] |
| **Algebraic Dependence** | ✓ (AM) | ✓ (coAM) | ? | ? | ? | [GSS18] |
| **Linear Programming** | ✓ | ✓ | ✓ | ✓ | ✓ | [Kar84], [Kha79],[Far02],[Hal07] |
| **Parity games** | ✓ | ✓ | ✓ | ✓ | ?* | [Jur98] , [BSV03] ; [CJK+17], [EJ91],[vdH25] |
| **Simple Stochastic Games** | ✓ | ✓ | ✓ | ? | ? | [Con92] , [Lud95] |
| **Mean-payoff games** | ✓ | ✓ | ✓ | ? | ? | [ZP96] , [Lud95] |
| **ARRIVAL problem** | ✓ | ✓ | ✓ | ? | ? | [DGK+17], [GHH21] |
| **Graph Isomorphism** | ✓ | ✓ (coAM) | ✓ | ✓ | ? | [BL83],[Bab85],[Bab16] |
| **Group Isomorphism** | ✓ | ✓ (coAM) | ✓ | ✓ | ? | [Mil78], [Bab85] |
| **Ring Isomorphism** | ✓ | ✓ (coAM) | ? | ? | ? | [KS06] |
| **Tensor Isomorphism** | ✓ | ✓ (coAM,*) | ? | ? | ? | [GQ21] |
| **Code Equivalence** | ✓ | ✓ (coAM) | ? | ? | ? | [PR02] |
| **Unique Game** | ✓ | ? | ✓ | ? | ? | [Kho02],[ABD15] |
| **GapCVP-$\sqrt{n}$** | ✓ | ✓ | ? | ? | ? | [AR04],[GG98] |
| **GapSVP-$\sqrt{n}$** | ✓ | ✓ | ? | ? | ? | [AR04],[GG98] |
| **3-Sphere Recognition** | ✓ | ✓ (GRH) | ? | ? | ? | [Sch11], [Zen18] |
| **Unknotting Problem** | ✓ | ✓ | ?* | ?* | ? | [HLP99] ; [Lac21] |
| **Statistical Difference** | ✓ (AM)| ✓ (coAM) | ? | ? | ? | [SV03] |
 
---
## Remarks

* SUBE refers to DTIME($2^{o(n)}$)
* Assume Derandomization, i.e. AM=NP, coAM=coNP, BPP=P
* A preprint [vdH25] claim parity game is in P
* A quasi-polynomial time algorithm for the Discrete Logarithm problem over *finite fields of fixed characteristic*.
* Tensor Isomorphism over finite fields is in NP ∩ coNP.
* A quasi-polynomial time algorithm for the Unknotting Problem was claimed by Lackenby in 2021. However, the result has not been formally published yet.


## References

* **[Adl79]** Adleman, L. (1979, October). A subexponential algorithm for the discrete logarithm problem with applications to cryptography. In Proceedings of the 20th Annual Symposium on Foundations of Computer Science (pp. 55-60).
* **[ABD15]** Arora, S., Barak, B., & Steurer, D. (2015). Subexponential algorithms for unique games and related problems. Journal of the ACM (JACM), 62(5), 1-25.
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
* **[Hal07]** Halman, N. (2007). Simple stochastic games, parity games, mean payoff games and discounted payoff games are all LP-type problems. Algorithmica, 49(1), 37-50.
* **[Jur98]** Jurdziński, M. (1998). Deciding the winner in parity games is in UP∩ co-UP. Information Processing Letters, 68(3), 119-124.
* **[KS06]** Kayal, N., & Saxena, N. (2006). Complexity of ring morphism problems. computational complexity, 15(4), 342-390.
* **[Kar84]** Karmarkar, N. (1984, December). A new polynomial-time algorithm for linear programming. In Proceedings of the sixteenth annual ACM symposium on Theory of computing (pp. 302-311).
* **[Kha79]** Khachiyan, L. G. (1979). *A polynomial algorithm in linear programming*.
* **[Kho02]** Khot, S. (2002, May). On the power of unique 2-prover 1-round games. In Proceedings of the thiry-fourth annual ACM symposium on Theory of computing (pp. 767-775).
* **[LLMP90]** Lenstra, A. K., Lenstra Jr, H. W., Manasse, M. S., & Pollard, J. M. (1990, April). The number field sieve. In Proceedings of the twenty-second annual ACM symposium on Theory of computing (pp. 564-572).
* **[Lac21]** Lackenby, M. (2021). The efficient certification of knottedness and Thurston norm. Advances in Mathematics, 387, 107796.
* **[Lud95]** Ludwig, W. (1995). A subexponential randomized algorithm for the simple stochastic game problem. Information and computation, 117(1), 151-155.
* **[PR02]** Petrank, E., & Roth, R. M. (2002). Is code equivalence easy to decide?. IEEE Transactions on Information Theory, 43(5), 1602-1604.
* **[Pom84]** Pomerance, C. (1984, April). The quadratic sieve factoring algorithm. In Workshop on the Theory and Application of of Cryptographic Techniques (pp. 169-182). Berlin, Heidelberg: Springer Berlin Heidelberg.
* **[Pra75]** Pratt, V. R. (1975). Every prime has a succinct certificate. SIAM Journal on Computing, 4(3), 214-220.
* **[GSS18]** Guo, Z., Saxena, N., & Sinhababu, A. (2019). Algebraic dependencies and PSPACE algorithms in approximative complexity over any field. Theory of Computing, 15(1), 1-30.
* **[SV03]** Sahai, A., & Vadhan, S. (2003). A complete problem for statistical zero knowledge. Journal of the ACM (JACM), 50(2), 196-249.
* **[Sch11]** Schleimer, S. (2011). Sphere recognition lies in NP. Low-dimensional and symplectic topology, 82(183-213), 1.
* **[Sho94]** Shor, P. W. (1994, November). Algorithms for quantum computation: discrete logarithms and factoring. In Proceedings 35th annual symposium on foundations of computer science (pp. 124-134). Ieee.
* **[Mil78]** Miller, G. L. (1978, May). On the nlog n isomorphism technique (a preliminary report). In Proceedings of the tenth annual ACM symposium on theory of computing (pp. 51-58).
* **[Thi94]** Thiel, Christoph. "Under the assumption of the Generalized Riemann Hypothesis verifying the class number belongs to NP∩ co-NP." International Algorithmic Number Theory Symposium. Berlin, Heidelberg: Springer Berlin Heidelberg, 1994.
* **[vdH25]** van der Heijden, R. (2025). Attractors Is All You Need: Parity Games In Polynomial Time. arXiv preprint arXiv:2511.03752.
* **[Zen18]** Zentner, R. (2018). Integer homology 3-spheres admit irreducible representations in SL (2, C).
* **[ZP96]** Zwick, U., & Paterson, M. (1996). The complexity of mean payoff games on graphs. Theoretical Computer Science, 158(1-2), 343-359.

## Acknowledge

The authors thank Zhengyang Liu for meaningful discussions covering TFNP, PPAD, UGC, and beyond. We also appreciate the valuable discussions with Anyu Wang, Wenhan Huang, and Yiding Feng, alongside EI, 142857cs, Tylemom, QingzhiMao, and Fast Photon from the UOJ community.

